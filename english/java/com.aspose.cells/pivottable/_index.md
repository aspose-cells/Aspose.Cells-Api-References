---
title: PivotTable
second_title: Aspose.Cells for Java API Reference
description: Summary description for PivotTable.
type: docs
weight: 413
url: /java/com.aspose.cells/pivottable/
---

**Inheritance:**
java.lang.Object
```
public class PivotTable
```

Summary description for PivotTable.

```
Workbook book = new Workbook();
         Worksheet sheet = book.getWorksheets().get(0);
         Cells cells = sheet.getCells();
         cells.get(0, 0).setValue("fruit");
         cells.get(1, 0).setValue("grape");
         cells.get(2, 0).setValue("blueberry");
         cells.get(3, 0).setValue("kiwi");
         cells.get(4, 0).setValue("cherry");
         cells.get(5, 0).setValue("grape");
         cells.get(6, 0).setValue("blueberry");
         cells.get(7, 0).setValue("kiwi");
         cells.get(8, 0).setValue("cherry");
 
         cells.get(0, 1).setValue("year");
         cells.get(1, 1).setValue(2020);
         cells.get(2, 1).setValue(2020);
         cells.get(3, 1).setValue(2020);
         cells.get(4, 1).setValue(2020);
         cells.get(5, 1).setValue(2021);
         cells.get(6, 1).setValue(2021);
         cells.get(7, 1).setValue(2021);
         cells.get(8, 1).setValue(2021);
 
         cells.get(0, 2).setValue("amount");
         cells.get(1, 2).setValue(50);
         cells.get(2, 2).setValue(60);
         cells.get(3, 2).setValue(70);
         cells.get(4, 2).setValue(80);
         cells.get(5, 2).setValue(90);
         cells.get(6, 2).setValue(100);
         cells.get(7, 2).setValue(110);
         cells.get(8, 2).setValue(120);
 
         PivotTableCollection pivots = sheet.getPivotTables();
 
         int pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable");
         PivotTable pivot = pivots.get(pivotIndex);
         pivot.addFieldToArea(PivotFieldType.ROW, "fruit");
         pivot.addFieldToArea(PivotFieldType.COLUMN, "year");
         pivot.addFieldToArea(PivotFieldType.DATA, "amount");
 
         pivot.setPivotTableStyleType(PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM_10);
 
         //Change PivotField's attributes
         PivotField rowField = pivot.getRowFields().get(0);
         rowField.setDisplayName("custom display name");
 
         //Add PivotFilter
         int index = pivot.getPivotFilters().add(0, PivotFilterType.COUNT);
         PivotFilter filter = pivot.getPivotFilters().get(index);
         filter.getAutoFilter().filterTop10(0, false, false, 2);
 
         //Add PivotFormatCondition
         int formatIndex = pivot.getPivotFormatConditions().add();
         PivotFormatCondition pfc = pivot.getPivotFormatConditions().get(formatIndex);
         FormatConditionCollection fcc = pfc.getFormatConditions();
         fcc.addArea(pivot.getDataBodyRange());
         int idx = fcc.addCondition(FormatConditionType.CELL_VALUE);
         FormatCondition fc = fcc.get(idx);
         fc.setFormula1("100");
         fc.setOperator(OperatorType.GREATER_OR_EQUAL);
         fc.getStyle().setBackgroundColor(Color.getRed());
 
         pivot.refreshData();
         pivot.calculateData();
 
         //do your business
 
         book.save("out.xlsx");
```
## Methods

| Method | Description |
| --- | --- |
| [addCalculatedField(String name, String formula)](#addCalculatedField-java.lang.String-java.lang.String-) | Adds a calculated field to pivot field and drag it to data area. |
| [addCalculatedField(String name, String formula, boolean dragToDataArea)](#addCalculatedField-java.lang.String-java.lang.String-boolean-) | Adds a calculated field to pivot field. |
| [addFieldToArea(int fieldType, PivotField pivotField)](#addFieldToArea-int-com.aspose.cells.PivotField-) | Adds the field to the specific area. |
| [addFieldToArea(int fieldType, int baseFieldIndex)](#addFieldToArea-int-int-) | Adds the field to the specific area. |
| [addFieldToArea(int fieldType, String fieldName)](#addFieldToArea-int-java.lang.String-) | Adds the field to the specific area. |
| [calculateData()](#calculateData--) | Calculates pivottable's data to cells. |
| [calculateRange()](#calculateRange--) | Calculates pivottable's range. |
| [changeDataSource(String[] source)](#changeDataSource-java.lang.String---) | Set pivottable's source data. |
| [clearData()](#clearData--) | Clear PivotTable's data and formatting If this method is not called before you add or delete PivotField, Maybe the PivotTable data is not corrected |
| [copyStyle(PivotTable pivotTable)](#copyStyle-com.aspose.cells.PivotTable-) | Copies named style from another pivot table. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fields(int fieldType)](#fields-int-) | Gets the specific fields by the field type. |
| [format(int row, int column, Style style)](#format-int-int-com.aspose.cells.Style-) | Format the cell in the pivottable area |
| [formatAll(Style style)](#formatAll-com.aspose.cells.Style-) | Format all the cell in the pivottable area |
| [formatRow(int row, Style style)](#formatRow-int-com.aspose.cells.Style-) | Format the row data in the pivottable area |
| [getAltTextDescription()](#getAltTextDescription--) | Gets the description of the alt text |
| [getAltTextTitle()](#getAltTextTitle--) | Gets the title of the altertext |
| [getAutoFormatType()](#getAutoFormatType--) | Gets the PivotTable auto format type. |
| [getBaseFields()](#getBaseFields--) | Returns a PivotFields object that includes all fields in the PivotTable report |
| [getCellByDisplayName(String displayName)](#getCellByDisplayName-java.lang.String-) | Gets the Cell object by the DisplayName of PivotField |
| [getChildren()](#getChildren--) | Gets the Children Pivot Tables which use this PivotTable data as data source. |
| [getClass()](#getClass--) |  |
| [getColumnFields()](#getColumnFields--) | Returns a PivotFields object that are currently shown as column fields. |
| [getColumnGrand()](#getColumnGrand--) | Indicates whether the PivotTable report shows grand totals for columns. |
| [getColumnHeaderCaption()](#getColumnHeaderCaption--) | Gets the Column Header Caption of the PivotTable. |
| [getColumnRange()](#getColumnRange--) | Returns a CellArea object that represents the range that contains the column area in the PivotTable report. |
| [getCustomListSort()](#getCustomListSort--) | Indicates whether consider built-in custom list when sort data |
| [getDataBodyRange()](#getDataBodyRange--) | Returns a CellArea object that represents the range that contains the data area in the list between the header row and the insert row. |
| [getDataField()](#getDataField--) | Gets a PivotField object that represents all the data fields in a PivotTable. |
| [getDataFields()](#getDataFields--) | Gets a PivotField object that represents all the data fields in a PivotTable. |
| [getDataSource()](#getDataSource--) | Gets and sets the data source of the pivot table. |
| [getDisplayErrorString()](#getDisplayErrorString--) | Indicates whether the PivotTable report displays a custom string in cells that contain errors. |
| [getDisplayImmediateItems()](#getDisplayImmediateItems--) | Indicates whether items in the row and column areas are visible when the data area of the PivotTable is empty. |
| [getDisplayNullString()](#getDisplayNullString--) | Indicates whether the PivotTable report displays a custom string in cells that contain null values. |
| [getEnableDataValueEditing()](#getEnableDataValueEditing--) | Specifies a boolean value that indicates whether the user is allowed to edit the cells in the data area of the pivottable. |
| [getEnableDrilldown()](#getEnableDrilldown--) | Gets whether drilldown is enabled. |
| [getEnableFieldDialog()](#getEnableFieldDialog--) | Indicates whether the PivotTable Field dialog box is available when the user double-clicks the PivotTable field. |
| [getEnableFieldList()](#getEnableFieldList--) | Gets whether enable the field list for the PivotTable. |
| [getEnableWizard()](#getEnableWizard--) | Indicates whether the PivotTable Wizard is available. |
| [getErrorString()](#getErrorString--) | Gets the string displayed in cells that contain errors when the DisplayErrorString property is true.The default value is an empty string. |
| [getExternalConnectionDataSource()](#getExternalConnectionDataSource--) | Gets the external connection data source. |
| [getFieldListSortAscending()](#getFieldListSortAscending--) | Specifies a boolean value that indicates whether fields in the PivotTable are sorted in non-default order in the field list. |
| [getGrandTotalName()](#getGrandTotalName--) | Returns the text string label that is displayed in the grand total column or row heading. |
| [getHorizontalBreaks()](#getHorizontalBreaks--) | get pivot table row index list of horizontal pagebreaks |
| [getIndent()](#getIndent--) | Specifies the indentation increment for compact axis and can be used to set the Report Layout to Compact Form. |
| [getItemPrintTitles()](#getItemPrintTitles--) | A bit that specifies whether pivot item captions on the row axis are repeated on each printed page for pivot fields in tabular form. |
| [getManualUpdate()](#getManualUpdate--) | Indicates whether the PivotTable report is recalculated only at the user's request. |
| [getMergeLabels()](#getMergeLabels--) | Indicates whether the specified PivotTable report's outer-row item, column item, subtotal, and grand total labels use merged cells. |
| [getMissingItemsLimit()](#getMissingItemsLimit--) | Specifies a boolean value that indicates whether the fields of a PivotTable can have multiple filters set on them. |
| [getName()](#getName--) | Gets the name of the PivotTable |
| [getNullString()](#getNullString--) | Gets the string displayed in cells that contain null values when the DisplayNullString property is true.The default value is an empty string. |
| [getPageFieldOrder()](#getPageFieldOrder--) | Gets the order in which page fields are added to the PivotTable report's layout. |
| [getPageFieldWrapCount()](#getPageFieldWrapCount--) | Gets the number of page fields in each column or row in the PivotTable report. |
| [getPageFields()](#getPageFields--) | Returns a PivotFields object that are currently shown as page fields. |
| [getPivotFilters()](#getPivotFilters--) | Returns a PivotFilterCollection object. |
| [getPivotFormatConditions()](#getPivotFormatConditions--) | Gets the Format Conditions of the pivot table. |
| [getPivotTableStyleName()](#getPivotTableStyleName--) | Gets and sets the pivottable style name. |
| [getPivotTableStyleType()](#getPivotTableStyleType--) | Gets and sets the built-in pivot table style. |
| [getPreserveFormatting()](#getPreserveFormatting--) | Indicates whether formatting is preserved when the PivotTable is refreshed or recalculated. |
| [getPrintDrill()](#getPrintDrill--) | Specifies a boolean value that indicates whether drill indicators should be printed. |
| [getPrintTitles()](#getPrintTitles--) | Indicates whether the print titles for the worksheet are set based on the PivotTable report. |
| [getRefreshDataFlag()](#getRefreshDataFlag--) | Indicates whether Refresh Data or not. |
| [getRefreshDataOnOpeningFile()](#getRefreshDataOnOpeningFile--) | Indicates whether Refresh Data when Opening File. |
| [getRefreshDate()](#getRefreshDate--) | Gets the date when the PivotTable was last refreshed. |
| [getRefreshedByWho()](#getRefreshedByWho--) | Gets the name of the user who last refreshed the PivotTable |
| [getRowFields()](#getRowFields--) | Returns a PivotFields object that are currently shown as row fields. |
| [getRowGrand()](#getRowGrand--) | Indicates whether the PivotTable report shows grand totals for rows. |
| [getRowHeaderCaption()](#getRowHeaderCaption--) | Gets the Row Header Caption of the PivotTable. |
| [getRowRange()](#getRowRange--) | Returns a CellArea object that represents the range that contains the row area in the PivotTable report. |
| [getSaveData()](#getSaveData--) | Indicates whether data for the PivotTable report is saved with the workbook. |
| [getShowDataTips()](#getShowDataTips--) | Specifies a boolean value that indicates whether tooltips should be displayed for PivotTable data cells. |
| [getShowDrill()](#getShowDrill--) | Gets whether expand/collapse buttons is shown. |
| [getShowEmptyCol()](#getShowEmptyCol--) | Specifies a boolean value that indicates whether to include empty columns in the table |
| [getShowEmptyRow()](#getShowEmptyRow--) | Specifies a boolean value that indicates whether to include empty rows in the table. |
| [getShowMemberPropertyTips()](#getShowMemberPropertyTips--) | Specifies a boolean value that indicates whether member property information should be omitted from PivotTable tooltips. |
| [getShowPivotStyleColumnHeader()](#getShowPivotStyleColumnHeader--) | Indicates whether the column header in the pivot table should have the style applied. |
| [getShowPivotStyleColumnStripes()](#getShowPivotStyleColumnStripes--) | Indicates whether column stripe formatting is applied. |
| [getShowPivotStyleLastColumn()](#getShowPivotStyleLastColumn--) | Indicates whether column stripe formatting is applied. |
| [getShowPivotStyleRowHeader()](#getShowPivotStyleRowHeader--) | Indicates whether the row header in the pivot table should have the style applied. |
| [getShowPivotStyleRowStripes()](#getShowPivotStyleRowStripes--) | Indicates whether row stripe formatting is applied. |
| [getShowRowHeaderCaption()](#getShowRowHeaderCaption--) | Indicates whether row header caption is shown in the PivotTable report Indicates whether Display field captions and filter drop downs |
| [getShowValuesRow()](#getShowValuesRow--) | Specifies a boolean value that indicates whether show values row. |
| [getSource()](#getSource--) | Get pivottable's source data. |
| [getSubtotalHiddenPageItems()](#getSubtotalHiddenPageItems--) | Indicates whether hidden page field items in the PivotTable report are included in row and column subtotals, block totals, and grand totals. |
| [getTableRange1()](#getTableRange1--) | Returns a CellArea object that represents the range containing the entire PivotTable report, but doesn't include page fields. |
| [getTableRange2()](#getTableRange2--) | Returns a CellArea object that represents the range containing the entire PivotTable report, includes page fields. |
| [getTag()](#getTag--) | Gets a string saved with the PivotTable report. |
| [hasBlankRows()](#hasBlankRows--) | Indicates whether to add blank rows. |
| [hashCode()](#hashCode--) |  |
| [isAutoFormat()](#isAutoFormat--) | Indicates whether the PivotTable report is automatically formatted. |
| [isExcel2003Compatible()](#isExcel2003Compatible--) | Specifies whether the PivotTable is compatible for Excel2003 when refreshing PivotTable, if true, a string must be less than or equal to 255 characters, so if the string is greater than 255 characters, it will be truncated. if false, a string will not have the aforementioned restriction. |
| [isGridDropZones()](#isGridDropZones--) | Indicates whether the PivotTable report displays classic pivottable layout. |
| [isMultipleFieldFilters()](#isMultipleFieldFilters--) | Specifies a boolean value that indicates whether the fields of a PivotTable can have multiple filters set on them. |
| [isSelected()](#isSelected--) | Indicates whether the PivotTable is selected. |
| [move(int row, int column)](#move-int-int-) | Moves the PivotTable to a different location in the worksheet. |
| [move(String destCellName)](#move-java.lang.String-) | Moves the PivotTable to a different location in the worksheet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Refreshes pivottable's data and setting from it's data source. |
| [removeField(int fieldType, PivotField pivotField)](#removeField-int-com.aspose.cells.PivotField-) | Remove field from specific field area |
| [removeField(int fieldType, int baseFieldIndex)](#removeField-int-int-) | Removes a field from specific field area |
| [removeField(int fieldType, String fieldName)](#removeField-int-java.lang.String-) | Removes a field from specific field area |
| [setAltTextDescription(String value)](#setAltTextDescription-java.lang.String-) | Please see the getter of this property: [getAltTextDescription()](../../com.aspose.cells/pivottable\#getAltTextDescription--) |
| [setAltTextTitle(String value)](#setAltTextTitle-java.lang.String-) | Please see the getter of this property: [getAltTextTitle()](../../com.aspose.cells/pivottable\#getAltTextTitle--) |
| [setAutoFormat(boolean value)](#setAutoFormat-boolean-) | Please see the getter of this property: [isAutoFormat()](../../com.aspose.cells/pivottable\#isAutoFormat--) |
| [setAutoFormatType(int value)](#setAutoFormatType-int-) | Please see the getter of this property: [getAutoFormatType()](../../com.aspose.cells/pivottable\#getAutoFormatType--) |
| [setAutoGroupField(PivotField pivotField)](#setAutoGroupField-com.aspose.cells.PivotField-) | Sets auto field group by the PivotTable. |
| [setAutoGroupField(int baseFieldIndex)](#setAutoGroupField-int-) | Sets auto field group by the PivotTable. |
| [setColumnGrand(boolean value)](#setColumnGrand-boolean-) | Please see the getter of this property: [getColumnGrand()](../../com.aspose.cells/pivottable\#getColumnGrand--) |
| [setColumnHeaderCaption(String value)](#setColumnHeaderCaption-java.lang.String-) | Please see the getter of this property: [getColumnHeaderCaption()](../../com.aspose.cells/pivottable\#getColumnHeaderCaption--) |
| [setCustomListSort(boolean value)](#setCustomListSort-boolean-) | Please see the getter of this property: [getCustomListSort()](../../com.aspose.cells/pivottable\#getCustomListSort--) |
| [setDataSource(String[] value)](#setDataSource-java.lang.String---) | Please see the getter of this property: [getDataSource()](../../com.aspose.cells/pivottable\#getDataSource--) |
| [setDisplayErrorString(boolean value)](#setDisplayErrorString-boolean-) | Please see the getter of this property: [getDisplayErrorString()](../../com.aspose.cells/pivottable\#getDisplayErrorString--) |
| [setDisplayImmediateItems(boolean value)](#setDisplayImmediateItems-boolean-) | Please see the getter of this property: [getDisplayImmediateItems()](../../com.aspose.cells/pivottable\#getDisplayImmediateItems--) |
| [setDisplayNullString(boolean value)](#setDisplayNullString-boolean-) | Please see the getter of this property: [getDisplayNullString()](../../com.aspose.cells/pivottable\#getDisplayNullString--) |
| [setEnableDataValueEditing(boolean value)](#setEnableDataValueEditing-boolean-) | Please see the getter of this property: [getEnableDataValueEditing()](../../com.aspose.cells/pivottable\#getEnableDataValueEditing--) |
| [setEnableDrilldown(boolean value)](#setEnableDrilldown-boolean-) | Please see the getter of this property: [getEnableDrilldown()](../../com.aspose.cells/pivottable\#getEnableDrilldown--) |
| [setEnableFieldDialog(boolean value)](#setEnableFieldDialog-boolean-) | Please see the getter of this property: [getEnableFieldDialog()](../../com.aspose.cells/pivottable\#getEnableFieldDialog--) |
| [setEnableFieldList(boolean value)](#setEnableFieldList-boolean-) | Please see the getter of this property: [getEnableFieldList()](../../com.aspose.cells/pivottable\#getEnableFieldList--) |
| [setEnableWizard(boolean value)](#setEnableWizard-boolean-) | Please see the getter of this property: [getEnableWizard()](../../com.aspose.cells/pivottable\#getEnableWizard--) |
| [setErrorString(String value)](#setErrorString-java.lang.String-) | Please see the getter of this property: [getErrorString()](../../com.aspose.cells/pivottable\#getErrorString--) |
| [setExcel2003Compatible(boolean value)](#setExcel2003Compatible-boolean-) | Please see the getter of this property: [isExcel2003Compatible()](../../com.aspose.cells/pivottable\#isExcel2003Compatible--) |
| [setFieldListSortAscending(boolean value)](#setFieldListSortAscending-boolean-) | Please see the getter of this property: [getFieldListSortAscending()](../../com.aspose.cells/pivottable\#getFieldListSortAscending--) |
| [setGrandTotalName(String value)](#setGrandTotalName-java.lang.String-) | Please see the getter of this property: [getGrandTotalName()](../../com.aspose.cells/pivottable\#getGrandTotalName--) |
| [setGridDropZones(boolean value)](#setGridDropZones-boolean-) | Please see the getter of this property: [isGridDropZones()](../../com.aspose.cells/pivottable\#isGridDropZones--) |
| [setHasBlankRows(boolean value)](#setHasBlankRows-boolean-) | Please see the getter of this property: [hasBlankRows()](../../com.aspose.cells/pivottable\#hasBlankRows--) |
| [setIndent(int value)](#setIndent-int-) | Please see the getter of this property: [getIndent()](../../com.aspose.cells/pivottable\#getIndent--) |
| [setItemPrintTitles(boolean value)](#setItemPrintTitles-boolean-) | Please see the getter of this property: [getItemPrintTitles()](../../com.aspose.cells/pivottable\#getItemPrintTitles--) |
| [setManualGroupField(PivotField pivotField, DateTime startVal, DateTime endVal, ArrayList groupByList, int intervalNum)](#setManualGroupField-com.aspose.cells.PivotField-com.aspose.cells.DateTime-com.aspose.cells.DateTime-java.util.ArrayList-int-) | Sets manual field group by the PivotTable. |
| [setManualGroupField(PivotField pivotField, double startVal, double endVal, ArrayList groupByList, double intervalNum)](#setManualGroupField-com.aspose.cells.PivotField-double-double-java.util.ArrayList-double-) | Sets manual field group by the PivotTable. |
| [setManualGroupField(int baseFieldIndex, DateTime startVal, DateTime endVal, ArrayList groupByList, int intervalNum)](#setManualGroupField-int-com.aspose.cells.DateTime-com.aspose.cells.DateTime-java.util.ArrayList-int-) | Sets manual field group by the PivotTable. |
| [setManualGroupField(int baseFieldIndex, double startVal, double endVal, ArrayList groupByList, double intervalNum)](#setManualGroupField-int-double-double-java.util.ArrayList-double-) | Sets manual field group by the PivotTable. |
| [setManualUpdate(boolean value)](#setManualUpdate-boolean-) | Please see the getter of this property: [getManualUpdate()](../../com.aspose.cells/pivottable\#getManualUpdate--) |
| [setMergeLabels(boolean value)](#setMergeLabels-boolean-) | Please see the getter of this property: [getMergeLabels()](../../com.aspose.cells/pivottable\#getMergeLabels--) |
| [setMissingItemsLimit(int value)](#setMissingItemsLimit-int-) | Please see the getter of this property: [getMissingItemsLimit()](../../com.aspose.cells/pivottable\#getMissingItemsLimit--) |
| [setMultipleFieldFilters(boolean value)](#setMultipleFieldFilters-boolean-) | Please see the getter of this property: [isMultipleFieldFilters()](../../com.aspose.cells/pivottable\#isMultipleFieldFilters--) |
| [setName(String value)](#setName-java.lang.String-) | Please see the getter of this property: [getName()](../../com.aspose.cells/pivottable\#getName--) |
| [setNullString(String value)](#setNullString-java.lang.String-) | Please see the getter of this property: [getNullString()](../../com.aspose.cells/pivottable\#getNullString--) |
| [setPageFieldOrder(int value)](#setPageFieldOrder-int-) | Please see the getter of this property: [getPageFieldOrder()](../../com.aspose.cells/pivottable\#getPageFieldOrder--) |
| [setPageFieldWrapCount(int value)](#setPageFieldWrapCount-int-) | Please see the getter of this property: [getPageFieldWrapCount()](../../com.aspose.cells/pivottable\#getPageFieldWrapCount--) |
| [setPivotTableStyleName(String value)](#setPivotTableStyleName-java.lang.String-) | Please see the getter of this property: [getPivotTableStyleName()](../../com.aspose.cells/pivottable\#getPivotTableStyleName--) |
| [setPivotTableStyleType(int value)](#setPivotTableStyleType-int-) | Please see the getter of this property: [getPivotTableStyleType()](../../com.aspose.cells/pivottable\#getPivotTableStyleType--) |
| [setPreserveFormatting(boolean value)](#setPreserveFormatting-boolean-) | Please see the getter of this property: [getPreserveFormatting()](../../com.aspose.cells/pivottable\#getPreserveFormatting--) |
| [setPrintDrill(boolean value)](#setPrintDrill-boolean-) | Please see the getter of this property: [getPrintDrill()](../../com.aspose.cells/pivottable\#getPrintDrill--) |
| [setPrintTitles(boolean value)](#setPrintTitles-boolean-) | Please see the getter of this property: [getPrintTitles()](../../com.aspose.cells/pivottable\#getPrintTitles--) |
| [setRefreshDataFlag(boolean value)](#setRefreshDataFlag-boolean-) | Please see the getter of this property: [getRefreshDataFlag()](../../com.aspose.cells/pivottable\#getRefreshDataFlag--) |
| [setRefreshDataOnOpeningFile(boolean value)](#setRefreshDataOnOpeningFile-boolean-) | Please see the getter of this property: [getRefreshDataOnOpeningFile()](../../com.aspose.cells/pivottable\#getRefreshDataOnOpeningFile--) |
| [setRowGrand(boolean value)](#setRowGrand-boolean-) | Please see the getter of this property: [getRowGrand()](../../com.aspose.cells/pivottable\#getRowGrand--) |
| [setRowHeaderCaption(String value)](#setRowHeaderCaption-java.lang.String-) | Please see the getter of this property: [getRowHeaderCaption()](../../com.aspose.cells/pivottable\#getRowHeaderCaption--) |
| [setSaveData(boolean value)](#setSaveData-boolean-) | Please see the getter of this property: [getSaveData()](../../com.aspose.cells/pivottable\#getSaveData--) |
| [setSelected(boolean value)](#setSelected-boolean-) | Please see the getter of this property: [isSelected()](../../com.aspose.cells/pivottable\#isSelected--) |
| [setShowDataTips(boolean value)](#setShowDataTips-boolean-) | Please see the getter of this property: [getShowDataTips()](../../com.aspose.cells/pivottable\#getShowDataTips--) |
| [setShowDrill(boolean value)](#setShowDrill-boolean-) | Please see the getter of this property: [getShowDrill()](../../com.aspose.cells/pivottable\#getShowDrill--) |
| [setShowEmptyCol(boolean value)](#setShowEmptyCol-boolean-) | Please see the getter of this property: [getShowEmptyCol()](../../com.aspose.cells/pivottable\#getShowEmptyCol--) |
| [setShowEmptyRow(boolean value)](#setShowEmptyRow-boolean-) | Please see the getter of this property: [getShowEmptyRow()](../../com.aspose.cells/pivottable\#getShowEmptyRow--) |
| [setShowMemberPropertyTips(boolean value)](#setShowMemberPropertyTips-boolean-) | Please see the getter of this property: [getShowMemberPropertyTips()](../../com.aspose.cells/pivottable\#getShowMemberPropertyTips--) |
| [setShowPivotStyleColumnHeader(boolean value)](#setShowPivotStyleColumnHeader-boolean-) | Please see the getter of this property: [getShowPivotStyleColumnHeader()](../../com.aspose.cells/pivottable\#getShowPivotStyleColumnHeader--) |
| [setShowPivotStyleColumnStripes(boolean value)](#setShowPivotStyleColumnStripes-boolean-) | Please see the getter of this property: [getShowPivotStyleColumnStripes()](../../com.aspose.cells/pivottable\#getShowPivotStyleColumnStripes--) |
| [setShowPivotStyleLastColumn(boolean value)](#setShowPivotStyleLastColumn-boolean-) | Please see the getter of this property: [getShowPivotStyleLastColumn()](../../com.aspose.cells/pivottable\#getShowPivotStyleLastColumn--) |
| [setShowPivotStyleRowHeader(boolean value)](#setShowPivotStyleRowHeader-boolean-) | Please see the getter of this property: [getShowPivotStyleRowHeader()](../../com.aspose.cells/pivottable\#getShowPivotStyleRowHeader--) |
| [setShowPivotStyleRowStripes(boolean value)](#setShowPivotStyleRowStripes-boolean-) | Please see the getter of this property: [getShowPivotStyleRowStripes()](../../com.aspose.cells/pivottable\#getShowPivotStyleRowStripes--) |
| [setShowRowHeaderCaption(boolean value)](#setShowRowHeaderCaption-boolean-) | Please see the getter of this property: [getShowRowHeaderCaption()](../../com.aspose.cells/pivottable\#getShowRowHeaderCaption--) |
| [setShowValuesRow(boolean value)](#setShowValuesRow-boolean-) | Please see the getter of this property: [getShowValuesRow()](../../com.aspose.cells/pivottable\#getShowValuesRow--) |
| [setSubtotalHiddenPageItems(boolean value)](#setSubtotalHiddenPageItems-boolean-) | Please see the getter of this property: [getSubtotalHiddenPageItems()](../../com.aspose.cells/pivottable\#getSubtotalHiddenPageItems--) |
| [setTag(String value)](#setTag-java.lang.String-) | Please see the getter of this property: [getTag()](../../com.aspose.cells/pivottable\#getTag--) |
| [setUngroup(PivotField pivotField)](#setUngroup-com.aspose.cells.PivotField-) | Sets ungroup by the PivotTable |
| [setUngroup(int baseFieldIndex)](#setUngroup-int-) | Sets ungroup by the PivotTable |
| [showInCompactForm()](#showInCompactForm--) | Layouts the PivotTable in compact form. |
| [showInOutlineForm()](#showInOutlineForm--) | Layouts the PivotTable in outline form. |
| [showInTabularForm()](#showInTabularForm--) | Layouts the PivotTable in tabular form. |
| [showReportFilterPage(PivotField pageField)](#showReportFilterPage-com.aspose.cells.PivotField-) | Show all the report filter pages according to PivotField, the PivotField must be located in the PageFields. |
| [showReportFilterPageByIndex(int posIndex)](#showReportFilterPageByIndex-int-) | Show all the report filter pages according to the position index in the PageFields |
| [showReportFilterPageByName(String fieldName)](#showReportFilterPageByName-java.lang.String-) | Show all the report filter pages according to PivotField's name, the PivotField must be located in the PageFields. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addCalculatedField(String name, String formula) {#addCalculatedField-java.lang.String-java.lang.String-}
```
public void addCalculatedField(String name, String formula)
```


Adds a calculated field to pivot field and drag it to data area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the calculated field |
| formula | java.lang.String | The formula of the calculated field. |

### addCalculatedField(String name, String formula, boolean dragToDataArea) {#addCalculatedField-java.lang.String-java.lang.String-boolean-}
```
public void addCalculatedField(String name, String formula, boolean dragToDataArea)
```


Adds a calculated field to pivot field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the calculated field |
| formula | java.lang.String | The formula of the calculated field. |
| dragToDataArea | boolean | True,drag this field to data area immediately |

### addFieldToArea(int fieldType, PivotField pivotField) {#addFieldToArea-int-com.aspose.cells.PivotField-}
```
public int addFieldToArea(int fieldType, PivotField pivotField)
```


Adds the field to the specific area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | the fields area type. |
| pivotField | [PivotField](../../com.aspose.cells/pivotfield) | the field in the base fields. |

**Returns:**
int - the field position in the specific fields.
### addFieldToArea(int fieldType, int baseFieldIndex) {#addFieldToArea-int-int-}
```
public int addFieldToArea(int fieldType, int baseFieldIndex)
```


Adds the field to the specific area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | The fields area type. |
| baseFieldIndex | int | The field index in the base fields. |

**Returns:**
int - The field position in the specific fields.
### addFieldToArea(int fieldType, String fieldName) {#addFieldToArea-int-java.lang.String-}
```
public int addFieldToArea(int fieldType, String fieldName)
```


Adds the field to the specific area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | The fields area type. |
| fieldName | java.lang.String | The name in the base fields. |

**Returns:**
int - The field position in the specific fields.If there is no field named as it, return -1.
### calculateData() {#calculateData--}
```
public void calculateData()
```


Calculates pivottable's data to cells. Cell.Value in the pivot range could not return the correct result if the method is not been called. This method calculates data with an inner pivot cache,not original data source. So if the data source is changed, please call RefreshData() method first.

### calculateRange() {#calculateRange--}
```
public void calculateRange()
```


Calculates pivottable's range. If this method is not been called,maybe the pivottable range is not corrected.

### changeDataSource(String[] source) {#changeDataSource-java.lang.String---}
```
public void changeDataSource(String[] source)
```


Set pivottable's source data. Sheet1!$A$1:$C$3

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String[] |  |

### clearData() {#clearData--}
```
public void clearData()
```


Clear PivotTable's data and formatting If this method is not called before you add or delete PivotField, Maybe the PivotTable data is not corrected

### copyStyle(PivotTable pivotTable) {#copyStyle-com.aspose.cells.PivotTable-}
```
public void copyStyle(PivotTable pivotTable)
```


Copies named style from another pivot table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pivotTable | [PivotTable](../../com.aspose.cells/pivottable) | Source pivot table. |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fields(int fieldType) {#fields-int-}
```
public PivotFieldCollection fields(int fieldType)
```


Gets the specific fields by the field type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | the field type. |

**Returns:**
[PivotFieldCollection](../../com.aspose.cells/pivotfieldcollection) - the specific fields
### format(int row, int column, Style style) {#format-int-int-com.aspose.cells.Style-}
```
public void format(int row, int column, Style style)
```


Format the cell in the pivottable area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | Row Index of the cell |
| column | int | Column index of the cell |
| style | [Style](../../com.aspose.cells/style) | Style which is to format the cell |

### formatAll(Style style) {#formatAll-com.aspose.cells.Style-}
```
public void formatAll(Style style)
```


Format all the cell in the pivottable area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | [Style](../../com.aspose.cells/style) | Style which is to format |

### formatRow(int row, Style style) {#formatRow-int-com.aspose.cells.Style-}
```
public void formatRow(int row, Style style)
```


Format the row data in the pivottable area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | Row Index of the Row object |
| style | [Style](../../com.aspose.cells/style) | Style which is to format |

### getAltTextDescription() {#getAltTextDescription--}
```
public String getAltTextDescription()
```


Gets the description of the alt text

**Returns:**
java.lang.String
### getAltTextTitle() {#getAltTextTitle--}
```
public String getAltTextTitle()
```


Gets the title of the altertext

**Returns:**
java.lang.String
### getAutoFormatType() {#getAutoFormatType--}
```
public int getAutoFormatType()
```


Gets the PivotTable auto format type.

**Returns:**
int
### getBaseFields() {#getBaseFields--}
```
public PivotFieldCollection getBaseFields()
```


Returns a PivotFields object that includes all fields in the PivotTable report

**Returns:**
[PivotFieldCollection](../../com.aspose.cells/pivotfieldcollection)
### getCellByDisplayName(String displayName) {#getCellByDisplayName-java.lang.String-}
```
public Cell getCellByDisplayName(String displayName)
```


Gets the Cell object by the DisplayName of PivotField

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | the DisplayName of PivotField |

**Returns:**
[Cell](../../com.aspose.cells/cell) - the Cell object
### getChildren() {#getChildren--}
```
public PivotTable[] getChildren()
```


Gets the Children Pivot Tables which use this PivotTable data as data source.

**Returns:**
com.aspose.cells.PivotTable[] - the PivotTable array object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnFields() {#getColumnFields--}
```
public PivotFieldCollection getColumnFields()
```


Returns a PivotFields object that are currently shown as column fields.

**Returns:**
[PivotFieldCollection](../../com.aspose.cells/pivotfieldcollection)
### getColumnGrand() {#getColumnGrand--}
```
public boolean getColumnGrand()
```


Indicates whether the PivotTable report shows grand totals for columns.

**Returns:**
boolean
### getColumnHeaderCaption() {#getColumnHeaderCaption--}
```
public String getColumnHeaderCaption()
```


Gets the Column Header Caption of the PivotTable.

**Returns:**
java.lang.String
### getColumnRange() {#getColumnRange--}
```
public CellArea getColumnRange()
```


Returns a CellArea object that represents the range that contains the column area in the PivotTable report. Read-only.

**Returns:**
[CellArea](../../com.aspose.cells/cellarea)
### getCustomListSort() {#getCustomListSort--}
```
public boolean getCustomListSort()
```


Indicates whether consider built-in custom list when sort data

**Returns:**
boolean
### getDataBodyRange() {#getDataBodyRange--}
```
public CellArea getDataBodyRange()
```


Returns a CellArea object that represents the range that contains the data area in the list between the header row and the insert row. Read-only.

**Returns:**
[CellArea](../../com.aspose.cells/cellarea)
### getDataField() {#getDataField--}
```
public PivotField getDataField()
```


Gets a PivotField object that represents all the data fields in a PivotTable. Read-only.It would be init only when there are two or more data fields in the DataPiovtFiels. It only use to add DataPivotField to the PivotTable row/column area . Default is in row area.

**Returns:**
[PivotField](../../com.aspose.cells/pivotfield)
### getDataFields() {#getDataFields--}
```
public PivotFieldCollection getDataFields()
```


Gets a PivotField object that represents all the data fields in a PivotTable. Read-only.It would be init only when there are two or more data fields in the DataPiovtFiels. It only use to add DataPivotField to the PivotTable row/column area . Default is in row area.

**Returns:**
[PivotFieldCollection](../../com.aspose.cells/pivotfieldcollection)
### getDataSource() {#getDataSource--}
```
public String[] getDataSource()
```


Gets and sets the data source of the pivot table.

**Returns:**
java.lang.String[]
### getDisplayErrorString() {#getDisplayErrorString--}
```
public boolean getDisplayErrorString()
```


Indicates whether the PivotTable report displays a custom string in cells that contain errors.

**Returns:**
boolean
### getDisplayImmediateItems() {#getDisplayImmediateItems--}
```
public boolean getDisplayImmediateItems()
```


Indicates whether items in the row and column areas are visible when the data area of the PivotTable is empty. The default value is true.

**Returns:**
boolean
### getDisplayNullString() {#getDisplayNullString--}
```
public boolean getDisplayNullString()
```


Indicates whether the PivotTable report displays a custom string in cells that contain null values.

**Returns:**
boolean
### getEnableDataValueEditing() {#getEnableDataValueEditing--}
```
public boolean getEnableDataValueEditing()
```


Specifies a boolean value that indicates whether the user is allowed to edit the cells in the data area of the pivottable. Enable cell editing in the values area

**Returns:**
boolean
### getEnableDrilldown() {#getEnableDrilldown--}
```
public boolean getEnableDrilldown()
```


Gets whether drilldown is enabled.

**Returns:**
boolean
### getEnableFieldDialog() {#getEnableFieldDialog--}
```
public boolean getEnableFieldDialog()
```


Indicates whether the PivotTable Field dialog box is available when the user double-clicks the PivotTable field.

**Returns:**
boolean
### getEnableFieldList() {#getEnableFieldList--}
```
public boolean getEnableFieldList()
```


Gets whether enable the field list for the PivotTable.

**Returns:**
boolean
### getEnableWizard() {#getEnableWizard--}
```
public boolean getEnableWizard()
```


Indicates whether the PivotTable Wizard is available.

**Returns:**
boolean
### getErrorString() {#getErrorString--}
```
public String getErrorString()
```


Gets the string displayed in cells that contain errors when the DisplayErrorString property is true.The default value is an empty string.

**Returns:**
java.lang.String
### getExternalConnectionDataSource() {#getExternalConnectionDataSource--}
```
public ExternalConnection getExternalConnectionDataSource()
```


Gets the external connection data source.

**Returns:**
[ExternalConnection](../../com.aspose.cells/externalconnection)
### getFieldListSortAscending() {#getFieldListSortAscending--}
```
public boolean getFieldListSortAscending()
```


Specifies a boolean value that indicates whether fields in the PivotTable are sorted in non-default order in the field list.

**Returns:**
boolean
### getGrandTotalName() {#getGrandTotalName--}
```
public String getGrandTotalName()
```


Returns the text string label that is displayed in the grand total column or row heading. The default value is the string "Grand Total".

**Returns:**
java.lang.String
### getHorizontalBreaks() {#getHorizontalBreaks--}
```
public ArrayList getHorizontalBreaks()
```


get pivot table row index list of horizontal pagebreaks

**Returns:**
java.util.ArrayList - 
### getIndent() {#getIndent--}
```
public int getIndent()
```


Specifies the indentation increment for compact axis and can be used to set the Report Layout to Compact Form.

**Returns:**
int
### getItemPrintTitles() {#getItemPrintTitles--}
```
public boolean getItemPrintTitles()
```


A bit that specifies whether pivot item captions on the row axis are repeated on each printed page for pivot fields in tabular form.

**Returns:**
boolean
### getManualUpdate() {#getManualUpdate--}
```
public boolean getManualUpdate()
```


Indicates whether the PivotTable report is recalculated only at the user's request.

**Returns:**
boolean
### getMergeLabels() {#getMergeLabels--}
```
public boolean getMergeLabels()
```


Indicates whether the specified PivotTable report's outer-row item, column item, subtotal, and grand total labels use merged cells.

**Returns:**
boolean
### getMissingItemsLimit() {#getMissingItemsLimit--}
```
public int getMissingItemsLimit()
```


Specifies a boolean value that indicates whether the fields of a PivotTable can have multiple filters set on them.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Gets the name of the PivotTable

**Returns:**
java.lang.String
### getNullString() {#getNullString--}
```
public String getNullString()
```


Gets the string displayed in cells that contain null values when the DisplayNullString property is true.The default value is an empty string.

**Returns:**
java.lang.String
### getPageFieldOrder() {#getPageFieldOrder--}
```
public int getPageFieldOrder()
```


Gets the order in which page fields are added to the PivotTable report's layout.

**Returns:**
int
### getPageFieldWrapCount() {#getPageFieldWrapCount--}
```
public int getPageFieldWrapCount()
```


Gets the number of page fields in each column or row in the PivotTable report.

**Returns:**
int
### getPageFields() {#getPageFields--}
```
public PivotFieldCollection getPageFields()
```


Returns a PivotFields object that are currently shown as page fields.

**Returns:**
[PivotFieldCollection](../../com.aspose.cells/pivotfieldcollection)
### getPivotFilters() {#getPivotFilters--}
```
public PivotFilterCollection getPivotFilters()
```


Returns a PivotFilterCollection object.

**Returns:**
[PivotFilterCollection](../../com.aspose.cells/pivotfiltercollection)
### getPivotFormatConditions() {#getPivotFormatConditions--}
```
public PivotFormatConditionCollection getPivotFormatConditions()
```


Gets the Format Conditions of the pivot table.

**Returns:**
[PivotFormatConditionCollection](../../com.aspose.cells/pivotformatconditioncollection)
### getPivotTableStyleName() {#getPivotTableStyleName--}
```
public String getPivotTableStyleName()
```


Gets and sets the pivottable style name.

**Returns:**
java.lang.String
### getPivotTableStyleType() {#getPivotTableStyleType--}
```
public int getPivotTableStyleType()
```


Gets and sets the built-in pivot table style.

**Returns:**
int
### getPreserveFormatting() {#getPreserveFormatting--}
```
public boolean getPreserveFormatting()
```


Indicates whether formatting is preserved when the PivotTable is refreshed or recalculated.

**Returns:**
boolean
### getPrintDrill() {#getPrintDrill--}
```
public boolean getPrintDrill()
```


Specifies a boolean value that indicates whether drill indicators should be printed. print expand/collapse buttons when displayed on pivottable.

**Returns:**
boolean
### getPrintTitles() {#getPrintTitles--}
```
public boolean getPrintTitles()
```


Indicates whether the print titles for the worksheet are set based on the PivotTable report. The default value is false.

**Returns:**
boolean
### getRefreshDataFlag() {#getRefreshDataFlag--}
```
public boolean getRefreshDataFlag()
```


Indicates whether Refresh Data or not.

**Returns:**
boolean
### getRefreshDataOnOpeningFile() {#getRefreshDataOnOpeningFile--}
```
public boolean getRefreshDataOnOpeningFile()
```


Indicates whether Refresh Data when Opening File.

**Returns:**
boolean
### getRefreshDate() {#getRefreshDate--}
```
public DateTime getRefreshDate()
```


Gets the date when the PivotTable was last refreshed.

**Returns:**
[DateTime](../../com.aspose.cells/datetime)
### getRefreshedByWho() {#getRefreshedByWho--}
```
public String getRefreshedByWho()
```


Gets the name of the user who last refreshed the PivotTable

**Returns:**
java.lang.String
### getRowFields() {#getRowFields--}
```
public PivotFieldCollection getRowFields()
```


Returns a PivotFields object that are currently shown as row fields.

**Returns:**
[PivotFieldCollection](../../com.aspose.cells/pivotfieldcollection)
### getRowGrand() {#getRowGrand--}
```
public boolean getRowGrand()
```


Indicates whether the PivotTable report shows grand totals for rows.

**Returns:**
boolean
### getRowHeaderCaption() {#getRowHeaderCaption--}
```
public String getRowHeaderCaption()
```


Gets the Row Header Caption of the PivotTable.

**Returns:**
java.lang.String
### getRowRange() {#getRowRange--}
```
public CellArea getRowRange()
```


Returns a CellArea object that represents the range that contains the row area in the PivotTable report. Read-only.

**Returns:**
[CellArea](../../com.aspose.cells/cellarea)
### getSaveData() {#getSaveData--}
```
public boolean getSaveData()
```


Indicates whether data for the PivotTable report is saved with the workbook.

**Returns:**
boolean
### getShowDataTips() {#getShowDataTips--}
```
public boolean getShowDataTips()
```


Specifies a boolean value that indicates whether tooltips should be displayed for PivotTable data cells.

**Returns:**
boolean
### getShowDrill() {#getShowDrill--}
```
public boolean getShowDrill()
```


Gets whether expand/collapse buttons is shown.

**Returns:**
boolean
### getShowEmptyCol() {#getShowEmptyCol--}
```
public boolean getShowEmptyCol()
```


Specifies a boolean value that indicates whether to include empty columns in the table

**Returns:**
boolean
### getShowEmptyRow() {#getShowEmptyRow--}
```
public boolean getShowEmptyRow()
```


Specifies a boolean value that indicates whether to include empty rows in the table.

**Returns:**
boolean
### getShowMemberPropertyTips() {#getShowMemberPropertyTips--}
```
public boolean getShowMemberPropertyTips()
```


Specifies a boolean value that indicates whether member property information should be omitted from PivotTable tooltips.

**Returns:**
boolean
### getShowPivotStyleColumnHeader() {#getShowPivotStyleColumnHeader--}
```
public boolean getShowPivotStyleColumnHeader()
```


Indicates whether the column header in the pivot table should have the style applied.

**Returns:**
boolean
### getShowPivotStyleColumnStripes() {#getShowPivotStyleColumnStripes--}
```
public boolean getShowPivotStyleColumnStripes()
```


Indicates whether column stripe formatting is applied.

**Returns:**
boolean
### getShowPivotStyleLastColumn() {#getShowPivotStyleLastColumn--}
```
public boolean getShowPivotStyleLastColumn()
```


Indicates whether column stripe formatting is applied.

**Returns:**
boolean
### getShowPivotStyleRowHeader() {#getShowPivotStyleRowHeader--}
```
public boolean getShowPivotStyleRowHeader()
```


Indicates whether the row header in the pivot table should have the style applied.

**Returns:**
boolean
### getShowPivotStyleRowStripes() {#getShowPivotStyleRowStripes--}
```
public boolean getShowPivotStyleRowStripes()
```


Indicates whether row stripe formatting is applied.

**Returns:**
boolean
### getShowRowHeaderCaption() {#getShowRowHeaderCaption--}
```
public boolean getShowRowHeaderCaption()
```


Indicates whether row header caption is shown in the PivotTable report Indicates whether Display field captions and filter drop downs

**Returns:**
boolean
### getShowValuesRow() {#getShowValuesRow--}
```
public boolean getShowValuesRow()
```


Specifies a boolean value that indicates whether show values row. show the values row

**Returns:**
boolean
### getSource() {#getSource--}
```
public String[] getSource()
```


Get pivottable's source data.

**Returns:**
java.lang.String[]
### getSubtotalHiddenPageItems() {#getSubtotalHiddenPageItems--}
```
public boolean getSubtotalHiddenPageItems()
```


Indicates whether hidden page field items in the PivotTable report are included in row and column subtotals, block totals, and grand totals. The default value is False.

**Returns:**
boolean
### getTableRange1() {#getTableRange1--}
```
public CellArea getTableRange1()
```


Returns a CellArea object that represents the range containing the entire PivotTable report, but doesn't include page fields. Read-only.

**Returns:**
[CellArea](../../com.aspose.cells/cellarea)
### getTableRange2() {#getTableRange2--}
```
public CellArea getTableRange2()
```


Returns a CellArea object that represents the range containing the entire PivotTable report, includes page fields. Read-only.

**Returns:**
[CellArea](../../com.aspose.cells/cellarea)
### getTag() {#getTag--}
```
public String getTag()
```


Gets a string saved with the PivotTable report.

**Returns:**
java.lang.String
### hasBlankRows() {#hasBlankRows--}
```
public boolean hasBlankRows()
```


Indicates whether to add blank rows. This property only applies for the PivotTable auto format types which needs to add blank rows.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoFormat() {#isAutoFormat--}
```
public boolean isAutoFormat()
```


Indicates whether the PivotTable report is automatically formatted. Checkbox "autoformat table " which is in pivottable option for Excel 2003 Checkbox "autofit column width on update" which is in pivot table Options :Layout Format for Excel 2007

**Returns:**
boolean
### isExcel2003Compatible() {#isExcel2003Compatible--}
```
public boolean isExcel2003Compatible()
```


Specifies whether the PivotTable is compatible for Excel2003 when refreshing PivotTable, if true, a string must be less than or equal to 255 characters, so if the string is greater than 255 characters, it will be truncated. if false, a string will not have the aforementioned restriction. The default value is true.

**Returns:**
boolean
### isGridDropZones() {#isGridDropZones--}
```
public boolean isGridDropZones()
```


Indicates whether the PivotTable report displays classic pivottable layout. (enables dragging fields in the grid)

**Returns:**
boolean
### isMultipleFieldFilters() {#isMultipleFieldFilters--}
```
public boolean isMultipleFieldFilters()
```


Specifies a boolean value that indicates whether the fields of a PivotTable can have multiple filters set on them.

**Returns:**
boolean
### isSelected() {#isSelected--}
```
public boolean isSelected()
```


Indicates whether the PivotTable is selected.

**Returns:**
boolean
### move(int row, int column) {#move-int-int-}
```
public void move(int row, int column)
```


Moves the PivotTable to a different location in the worksheet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | row index. |
| column | int | column index. |

### move(String destCellName) {#move-java.lang.String-}
```
public void move(String destCellName)
```


Moves the PivotTable to a different location in the worksheet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destCellName | java.lang.String | the dest cell name. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Refreshes pivottable's data and setting from it's data source. We will gather data from data source to a pivot cache ,then calculate the data in the cache to the cells. This method is only used to gather all data to a pivot cache.

### removeField(int fieldType, PivotField pivotField) {#removeField-int-com.aspose.cells.PivotField-}
```
public void removeField(int fieldType, PivotField pivotField)
```


Remove field from specific field area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | the fields area type. |
| pivotField | [PivotField](../../com.aspose.cells/pivotfield) | the field in the base fields. |

### removeField(int fieldType, int baseFieldIndex) {#removeField-int-int-}
```
public void removeField(int fieldType, int baseFieldIndex)
```


Removes a field from specific field area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | The fields area type. |
| baseFieldIndex | int | The field index in the base fields. |

### removeField(int fieldType, String fieldName) {#removeField-int-java.lang.String-}
```
public void removeField(int fieldType, String fieldName)
```


Removes a field from specific field area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | The fields area type. |
| fieldName | java.lang.String | The name in the base fields. |

### setAltTextDescription(String value) {#setAltTextDescription-java.lang.String-}
```
public void setAltTextDescription(String value)
```


Please see the getter of this property: [getAltTextDescription()](../../com.aspose.cells/pivottable\#getAltTextDescription--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setAltTextTitle(String value) {#setAltTextTitle-java.lang.String-}
```
public void setAltTextTitle(String value)
```


Please see the getter of this property: [getAltTextTitle()](../../com.aspose.cells/pivottable\#getAltTextTitle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setAutoFormat(boolean value) {#setAutoFormat-boolean-}
```
public void setAutoFormat(boolean value)
```


Please see the getter of this property: [isAutoFormat()](../../com.aspose.cells/pivottable\#isAutoFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAutoFormatType(int value) {#setAutoFormatType-int-}
```
public void setAutoFormatType(int value)
```


Please see the getter of this property: [getAutoFormatType()](../../com.aspose.cells/pivottable\#getAutoFormatType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setAutoGroupField(PivotField pivotField) {#setAutoGroupField-com.aspose.cells.PivotField-}
```
public void setAutoGroupField(PivotField pivotField)
```


Sets auto field group by the PivotTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pivotField | [PivotField](../../com.aspose.cells/pivotfield) | The row or column field in the specific fields |

### setAutoGroupField(int baseFieldIndex) {#setAutoGroupField-int-}
```
public void setAutoGroupField(int baseFieldIndex)
```


Sets auto field group by the PivotTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseFieldIndex | int | The row or column field index in the base fields |

### setColumnGrand(boolean value) {#setColumnGrand-boolean-}
```
public void setColumnGrand(boolean value)
```


Please see the getter of this property: [getColumnGrand()](../../com.aspose.cells/pivottable\#getColumnGrand--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setColumnHeaderCaption(String value) {#setColumnHeaderCaption-java.lang.String-}
```
public void setColumnHeaderCaption(String value)
```


Please see the getter of this property: [getColumnHeaderCaption()](../../com.aspose.cells/pivottable\#getColumnHeaderCaption--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomListSort(boolean value) {#setCustomListSort-boolean-}
```
public void setCustomListSort(boolean value)
```


Please see the getter of this property: [getCustomListSort()](../../com.aspose.cells/pivottable\#getCustomListSort--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDataSource(String[] value) {#setDataSource-java.lang.String---}
```
public void setDataSource(String[] value)
```


Please see the getter of this property: [getDataSource()](../../com.aspose.cells/pivottable\#getDataSource--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDisplayErrorString(boolean value) {#setDisplayErrorString-boolean-}
```
public void setDisplayErrorString(boolean value)
```


Please see the getter of this property: [getDisplayErrorString()](../../com.aspose.cells/pivottable\#getDisplayErrorString--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDisplayImmediateItems(boolean value) {#setDisplayImmediateItems-boolean-}
```
public void setDisplayImmediateItems(boolean value)
```


Please see the getter of this property: [getDisplayImmediateItems()](../../com.aspose.cells/pivottable\#getDisplayImmediateItems--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDisplayNullString(boolean value) {#setDisplayNullString-boolean-}
```
public void setDisplayNullString(boolean value)
```


Please see the getter of this property: [getDisplayNullString()](../../com.aspose.cells/pivottable\#getDisplayNullString--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnableDataValueEditing(boolean value) {#setEnableDataValueEditing-boolean-}
```
public void setEnableDataValueEditing(boolean value)
```


Please see the getter of this property: [getEnableDataValueEditing()](../../com.aspose.cells/pivottable\#getEnableDataValueEditing--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnableDrilldown(boolean value) {#setEnableDrilldown-boolean-}
```
public void setEnableDrilldown(boolean value)
```


Please see the getter of this property: [getEnableDrilldown()](../../com.aspose.cells/pivottable\#getEnableDrilldown--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnableFieldDialog(boolean value) {#setEnableFieldDialog-boolean-}
```
public void setEnableFieldDialog(boolean value)
```


Please see the getter of this property: [getEnableFieldDialog()](../../com.aspose.cells/pivottable\#getEnableFieldDialog--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnableFieldList(boolean value) {#setEnableFieldList-boolean-}
```
public void setEnableFieldList(boolean value)
```


Please see the getter of this property: [getEnableFieldList()](../../com.aspose.cells/pivottable\#getEnableFieldList--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEnableWizard(boolean value) {#setEnableWizard-boolean-}
```
public void setEnableWizard(boolean value)
```


Please see the getter of this property: [getEnableWizard()](../../com.aspose.cells/pivottable\#getEnableWizard--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setErrorString(String value) {#setErrorString-java.lang.String-}
```
public void setErrorString(String value)
```


Please see the getter of this property: [getErrorString()](../../com.aspose.cells/pivottable\#getErrorString--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setExcel2003Compatible(boolean value) {#setExcel2003Compatible-boolean-}
```
public void setExcel2003Compatible(boolean value)
```


Please see the getter of this property: [isExcel2003Compatible()](../../com.aspose.cells/pivottable\#isExcel2003Compatible--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFieldListSortAscending(boolean value) {#setFieldListSortAscending-boolean-}
```
public void setFieldListSortAscending(boolean value)
```


Please see the getter of this property: [getFieldListSortAscending()](../../com.aspose.cells/pivottable\#getFieldListSortAscending--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGrandTotalName(String value) {#setGrandTotalName-java.lang.String-}
```
public void setGrandTotalName(String value)
```


Please see the getter of this property: [getGrandTotalName()](../../com.aspose.cells/pivottable\#getGrandTotalName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setGridDropZones(boolean value) {#setGridDropZones-boolean-}
```
public void setGridDropZones(boolean value)
```


Please see the getter of this property: [isGridDropZones()](../../com.aspose.cells/pivottable\#isGridDropZones--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHasBlankRows(boolean value) {#setHasBlankRows-boolean-}
```
public void setHasBlankRows(boolean value)
```


Please see the getter of this property: [hasBlankRows()](../../com.aspose.cells/pivottable\#hasBlankRows--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setIndent(int value) {#setIndent-int-}
```
public void setIndent(int value)
```


Please see the getter of this property: [getIndent()](../../com.aspose.cells/pivottable\#getIndent--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setItemPrintTitles(boolean value) {#setItemPrintTitles-boolean-}
```
public void setItemPrintTitles(boolean value)
```


Please see the getter of this property: [getItemPrintTitles()](../../com.aspose.cells/pivottable\#getItemPrintTitles--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setManualGroupField(PivotField pivotField, DateTime startVal, DateTime endVal, ArrayList groupByList, int intervalNum) {#setManualGroupField-com.aspose.cells.PivotField-com.aspose.cells.DateTime-com.aspose.cells.DateTime-java.util.ArrayList-int-}
```
public void setManualGroupField(PivotField pivotField, DateTime startVal, DateTime endVal, ArrayList groupByList, int intervalNum)
```


Sets manual field group by the PivotTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pivotField | [PivotField](../../com.aspose.cells/pivotfield) | The row or column field in the base fields |
| startVal | [DateTime](../../com.aspose.cells/datetime) | Specifies the starting value for date grouping. |
| endVal | [DateTime](../../com.aspose.cells/datetime) | Specifies the ending value for date grouping. |
| groupByList | java.util.ArrayList | Specifies the grouping type list. Specified by PivotTableGroupType |
| intervalNum | int | Specifies the interval number group by in days grouping.The number of days must be positive integer of nonzero |

### setManualGroupField(PivotField pivotField, double startVal, double endVal, ArrayList groupByList, double intervalNum) {#setManualGroupField-com.aspose.cells.PivotField-double-double-java.util.ArrayList-double-}
```
public void setManualGroupField(PivotField pivotField, double startVal, double endVal, ArrayList groupByList, double intervalNum)
```


Sets manual field group by the PivotTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pivotField | [PivotField](../../com.aspose.cells/pivotfield) | The row or column field in the base fields |
| startVal | double | Specifies the starting value for numeric grouping. |
| endVal | double | Specifies the ending value for numeric grouping. |
| groupByList | java.util.ArrayList | Specifies the grouping type list. Specified by PivotTableGroupType |
| intervalNum | double | Specifies the interval number group by numeric grouping. |

### setManualGroupField(int baseFieldIndex, DateTime startVal, DateTime endVal, ArrayList groupByList, int intervalNum) {#setManualGroupField-int-com.aspose.cells.DateTime-com.aspose.cells.DateTime-java.util.ArrayList-int-}
```
public void setManualGroupField(int baseFieldIndex, DateTime startVal, DateTime endVal, ArrayList groupByList, int intervalNum)
```


Sets manual field group by the PivotTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseFieldIndex | int | The row or column field index in the base fields |
| startVal | [DateTime](../../com.aspose.cells/datetime) | Specifies the starting value for date grouping. |
| endVal | [DateTime](../../com.aspose.cells/datetime) | Specifies the ending value for date grouping. |
| groupByList | java.util.ArrayList | Specifies the grouping type list. Specified by PivotTableGroupType |
| intervalNum | int | Specifies the interval number group by in days grouping.The number of days must be positive integer of nonzero |

### setManualGroupField(int baseFieldIndex, double startVal, double endVal, ArrayList groupByList, double intervalNum) {#setManualGroupField-int-double-double-java.util.ArrayList-double-}
```
public void setManualGroupField(int baseFieldIndex, double startVal, double endVal, ArrayList groupByList, double intervalNum)
```


Sets manual field group by the PivotTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseFieldIndex | int | The row or column field index in the base fields |
| startVal | double | Specifies the starting value for numeric grouping. |
| endVal | double | Specifies the ending value for numeric grouping. |
| groupByList | java.util.ArrayList | Specifies the grouping type list. Specified by PivotTableGroupType |
| intervalNum | double | Specifies the interval number group by numeric grouping. |

### setManualUpdate(boolean value) {#setManualUpdate-boolean-}
```
public void setManualUpdate(boolean value)
```


Please see the getter of this property: [getManualUpdate()](../../com.aspose.cells/pivottable\#getManualUpdate--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMergeLabels(boolean value) {#setMergeLabels-boolean-}
```
public void setMergeLabels(boolean value)
```


Please see the getter of this property: [getMergeLabels()](../../com.aspose.cells/pivottable\#getMergeLabels--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMissingItemsLimit(int value) {#setMissingItemsLimit-int-}
```
public void setMissingItemsLimit(int value)
```


Please see the getter of this property: [getMissingItemsLimit()](../../com.aspose.cells/pivottable\#getMissingItemsLimit--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMultipleFieldFilters(boolean value) {#setMultipleFieldFilters-boolean-}
```
public void setMultipleFieldFilters(boolean value)
```


Please see the getter of this property: [isMultipleFieldFilters()](../../com.aspose.cells/pivottable\#isMultipleFieldFilters--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Please see the getter of this property: [getName()](../../com.aspose.cells/pivottable\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNullString(String value) {#setNullString-java.lang.String-}
```
public void setNullString(String value)
```


Please see the getter of this property: [getNullString()](../../com.aspose.cells/pivottable\#getNullString--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPageFieldOrder(int value) {#setPageFieldOrder-int-}
```
public void setPageFieldOrder(int value)
```


Please see the getter of this property: [getPageFieldOrder()](../../com.aspose.cells/pivottable\#getPageFieldOrder--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageFieldWrapCount(int value) {#setPageFieldWrapCount-int-}
```
public void setPageFieldWrapCount(int value)
```


Please see the getter of this property: [getPageFieldWrapCount()](../../com.aspose.cells/pivottable\#getPageFieldWrapCount--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPivotTableStyleName(String value) {#setPivotTableStyleName-java.lang.String-}
```
public void setPivotTableStyleName(String value)
```


Please see the getter of this property: [getPivotTableStyleName()](../../com.aspose.cells/pivottable\#getPivotTableStyleName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPivotTableStyleType(int value) {#setPivotTableStyleType-int-}
```
public void setPivotTableStyleType(int value)
```


Please see the getter of this property: [getPivotTableStyleType()](../../com.aspose.cells/pivottable\#getPivotTableStyleType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPreserveFormatting(boolean value) {#setPreserveFormatting-boolean-}
```
public void setPreserveFormatting(boolean value)
```


Please see the getter of this property: [getPreserveFormatting()](../../com.aspose.cells/pivottable\#getPreserveFormatting--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPrintDrill(boolean value) {#setPrintDrill-boolean-}
```
public void setPrintDrill(boolean value)
```


Please see the getter of this property: [getPrintDrill()](../../com.aspose.cells/pivottable\#getPrintDrill--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPrintTitles(boolean value) {#setPrintTitles-boolean-}
```
public void setPrintTitles(boolean value)
```


Please see the getter of this property: [getPrintTitles()](../../com.aspose.cells/pivottable\#getPrintTitles--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRefreshDataFlag(boolean value) {#setRefreshDataFlag-boolean-}
```
public void setRefreshDataFlag(boolean value)
```


Please see the getter of this property: [getRefreshDataFlag()](../../com.aspose.cells/pivottable\#getRefreshDataFlag--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRefreshDataOnOpeningFile(boolean value) {#setRefreshDataOnOpeningFile-boolean-}
```
public void setRefreshDataOnOpeningFile(boolean value)
```


Please see the getter of this property: [getRefreshDataOnOpeningFile()](../../com.aspose.cells/pivottable\#getRefreshDataOnOpeningFile--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRowGrand(boolean value) {#setRowGrand-boolean-}
```
public void setRowGrand(boolean value)
```


Please see the getter of this property: [getRowGrand()](../../com.aspose.cells/pivottable\#getRowGrand--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRowHeaderCaption(String value) {#setRowHeaderCaption-java.lang.String-}
```
public void setRowHeaderCaption(String value)
```


Please see the getter of this property: [getRowHeaderCaption()](../../com.aspose.cells/pivottable\#getRowHeaderCaption--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSaveData(boolean value) {#setSaveData-boolean-}
```
public void setSaveData(boolean value)
```


Please see the getter of this property: [getSaveData()](../../com.aspose.cells/pivottable\#getSaveData--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSelected(boolean value) {#setSelected-boolean-}
```
public void setSelected(boolean value)
```


Please see the getter of this property: [isSelected()](../../com.aspose.cells/pivottable\#isSelected--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowDataTips(boolean value) {#setShowDataTips-boolean-}
```
public void setShowDataTips(boolean value)
```


Please see the getter of this property: [getShowDataTips()](../../com.aspose.cells/pivottable\#getShowDataTips--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowDrill(boolean value) {#setShowDrill-boolean-}
```
public void setShowDrill(boolean value)
```


Please see the getter of this property: [getShowDrill()](../../com.aspose.cells/pivottable\#getShowDrill--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowEmptyCol(boolean value) {#setShowEmptyCol-boolean-}
```
public void setShowEmptyCol(boolean value)
```


Please see the getter of this property: [getShowEmptyCol()](../../com.aspose.cells/pivottable\#getShowEmptyCol--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowEmptyRow(boolean value) {#setShowEmptyRow-boolean-}
```
public void setShowEmptyRow(boolean value)
```


Please see the getter of this property: [getShowEmptyRow()](../../com.aspose.cells/pivottable\#getShowEmptyRow--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowMemberPropertyTips(boolean value) {#setShowMemberPropertyTips-boolean-}
```
public void setShowMemberPropertyTips(boolean value)
```


Please see the getter of this property: [getShowMemberPropertyTips()](../../com.aspose.cells/pivottable\#getShowMemberPropertyTips--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowPivotStyleColumnHeader(boolean value) {#setShowPivotStyleColumnHeader-boolean-}
```
public void setShowPivotStyleColumnHeader(boolean value)
```


Please see the getter of this property: [getShowPivotStyleColumnHeader()](../../com.aspose.cells/pivottable\#getShowPivotStyleColumnHeader--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowPivotStyleColumnStripes(boolean value) {#setShowPivotStyleColumnStripes-boolean-}
```
public void setShowPivotStyleColumnStripes(boolean value)
```


Please see the getter of this property: [getShowPivotStyleColumnStripes()](../../com.aspose.cells/pivottable\#getShowPivotStyleColumnStripes--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowPivotStyleLastColumn(boolean value) {#setShowPivotStyleLastColumn-boolean-}
```
public void setShowPivotStyleLastColumn(boolean value)
```


Please see the getter of this property: [getShowPivotStyleLastColumn()](../../com.aspose.cells/pivottable\#getShowPivotStyleLastColumn--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowPivotStyleRowHeader(boolean value) {#setShowPivotStyleRowHeader-boolean-}
```
public void setShowPivotStyleRowHeader(boolean value)
```


Please see the getter of this property: [getShowPivotStyleRowHeader()](../../com.aspose.cells/pivottable\#getShowPivotStyleRowHeader--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowPivotStyleRowStripes(boolean value) {#setShowPivotStyleRowStripes-boolean-}
```
public void setShowPivotStyleRowStripes(boolean value)
```


Please see the getter of this property: [getShowPivotStyleRowStripes()](../../com.aspose.cells/pivottable\#getShowPivotStyleRowStripes--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowRowHeaderCaption(boolean value) {#setShowRowHeaderCaption-boolean-}
```
public void setShowRowHeaderCaption(boolean value)
```


Please see the getter of this property: [getShowRowHeaderCaption()](../../com.aspose.cells/pivottable\#getShowRowHeaderCaption--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShowValuesRow(boolean value) {#setShowValuesRow-boolean-}
```
public void setShowValuesRow(boolean value)
```


Please see the getter of this property: [getShowValuesRow()](../../com.aspose.cells/pivottable\#getShowValuesRow--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSubtotalHiddenPageItems(boolean value) {#setSubtotalHiddenPageItems-boolean-}
```
public void setSubtotalHiddenPageItems(boolean value)
```


Please see the getter of this property: [getSubtotalHiddenPageItems()](../../com.aspose.cells/pivottable\#getSubtotalHiddenPageItems--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTag(String value) {#setTag-java.lang.String-}
```
public void setTag(String value)
```


Please see the getter of this property: [getTag()](../../com.aspose.cells/pivottable\#getTag--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setUngroup(PivotField pivotField) {#setUngroup-com.aspose.cells.PivotField-}
```
public void setUngroup(PivotField pivotField)
```


Sets ungroup by the PivotTable

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pivotField | [PivotField](../../com.aspose.cells/pivotfield) | The row or column field in the base fields |

### setUngroup(int baseFieldIndex) {#setUngroup-int-}
```
public void setUngroup(int baseFieldIndex)
```


Sets ungroup by the PivotTable

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseFieldIndex | int | The row or column field index in the base fields |

### showInCompactForm() {#showInCompactForm--}
```
public void showInCompactForm()
```


Layouts the PivotTable in compact form.

### showInOutlineForm() {#showInOutlineForm--}
```
public void showInOutlineForm()
```


Layouts the PivotTable in outline form.

### showInTabularForm() {#showInTabularForm--}
```
public void showInTabularForm()
```


Layouts the PivotTable in tabular form.

### showReportFilterPage(PivotField pageField) {#showReportFilterPage-com.aspose.cells.PivotField-}
```
public void showReportFilterPage(PivotField pageField)
```


Show all the report filter pages according to PivotField, the PivotField must be located in the PageFields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageField | [PivotField](../../com.aspose.cells/pivotfield) | The PivotField object |

### showReportFilterPageByIndex(int posIndex) {#showReportFilterPageByIndex-int-}
```
public void showReportFilterPageByIndex(int posIndex)
```


Show all the report filter pages according to the position index in the PageFields

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| posIndex | int | The position index in the PageFields |

### showReportFilterPageByName(String fieldName) {#showReportFilterPageByName-java.lang.String-}
```
public void showReportFilterPageByName(String fieldName)
```


Show all the report filter pages according to PivotField's name, the PivotField must be located in the PageFields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The name of PivotField |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
