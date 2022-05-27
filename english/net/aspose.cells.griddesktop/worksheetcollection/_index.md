---
title: WorksheetCollection
second_title: Aspose.Cells for .NET API Reference
description: 
type: docs
weight: 1090
url: /net/aspose.cells.griddesktop/worksheetcollection/
---
## WorksheetCollection class

Collects the  objects that represent the individual rows in a worksheet.

```csharp
public class WorksheetCollection
```

## Properties

| Name | Description |
| --- | --- |
| [ActiveSheetIndex](../../aspose.cells.griddesktop/worksheetcollection/activesheetindex) { get; set; } |  |
| [Count](../../aspose.cells.griddesktop/worksheetcollection/count) { get; } |  |
| [DefaultFontName](../../aspose.cells.griddesktop/worksheetcollection/defaultfontname) { get; set; } | Gets or sets the control's default font name. |
| [Item](../../aspose.cells.griddesktop/worksheetcollection/item) { get; } | Gets the [`Worksheet`](../worksheet) element at the specified index. (2 indexers) |
| [Names](../../aspose.cells.griddesktop/worksheetcollection/names) { get; } | Gets the collection of all the Name objects in the spreadsheet. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.cells.griddesktop/worksheetcollection/add)() | Adds a worksheet to the collection. |
| [Add](../../aspose.cells.griddesktop/worksheetcollection/add)(string) | Adds a worksheet to the collection. |
| [AddCopy](../../aspose.cells.griddesktop/worksheetcollection/addcopy)(int) | Adds a worksheet to the collection and copies data from an existed worksheet. |
| [AddCopy](../../aspose.cells.griddesktop/worksheetcollection/addcopy)(string) | Adds a worksheet to the collection and copies data from an existed worksheet. |
| [CalculateFormula](../../aspose.cells.griddesktop/worksheetcollection/calculateformula)() | Calculates the result of formulas. |
| [Clear](../../aspose.cells.griddesktop/worksheetcollection/clear)() | Clear all worksheets. |
| [GetEnumerator](../../aspose.cells.griddesktop/worksheetcollection/getenumerator)() | Gets the rows enumerator |
| [IndexOf](../../aspose.cells.griddesktop/worksheetcollection/indexof)(Worksheet) | Searches for the specified sheet and returns the zero-based index of the first occurrence within the entire WorksheetCollection. |
| [Insert](../../aspose.cells.griddesktop/worksheetcollection/insert)(int) | Inserts an worksheet into the WorksheetCollection at the specified index. This worksheet row count is 256,column count is 32. The worksheet name will be generated by Add() method. |
| [Insert](../../aspose.cells.griddesktop/worksheetcollection/insert)(int, string) |  |
| [MoveTo](../../aspose.cells.griddesktop/worksheetcollection/moveto)(int, int) |  |
| [Remove](../../aspose.cells.griddesktop/worksheetcollection/remove)(int) | Removes the worksheet at the specified index of the WorksheetCollection. If the specific sheet is the last sheet,after removes sheet,will add a new sheet to the WorksheetCollection. |
| [RemoveAt](../../aspose.cells.griddesktop/worksheetcollection/removeat)(int) | Removes the element at a specified index. |
| [RemoveAt](../../aspose.cells.griddesktop/worksheetcollection/removeat)(string) | Removes the element at a specified name. |
| [SetVisible](../../aspose.cells.griddesktop/worksheetcollection/setvisible)(string, bool) | Sets the visible options. |
| [SwapSheet](../../aspose.cells.griddesktop/worksheetcollection/swapsheet)(int, int) | Swaps the two sheets. |

### See Also

* namespace [Aspose.Cells.GridDesktop](../../aspose.cells.griddesktop)
* assembly [Aspose.Cells.GridDesktop](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->