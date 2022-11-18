---
title: AbstractTextLoadOptions
second_title: Aspose.Cells for Java API Reference
description: Common options for loading text values
type: docs
weight: 15
url: /java/com.aspose.cells/abstracttextloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.cells.LoadOptions](../../com.aspose.cells/loadoptions)
```
public class AbstractTextLoadOptions extends LoadOptions
```

Common options for loading text values
## Constructors

| Constructor | Description |
| --- | --- |
| [AbstractTextLoadOptions()](#AbstractTextLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFilter()](#getAutoFilter--) | Indicates whether auto filtering the data when loading the files. |
| [getAutoFitterOptions()](#getAutoFitterOptions--) | Gets and sets the auto fitter options Only for xlsx ,spreadsheetML file now. |
| [getCheckDataValid()](#getCheckDataValid--) | Check whether data is valid in the template file. |
| [getCheckExcelRestriction()](#getCheckExcelRestriction--) | Whether check restriction of excel file when user modify cells related objects. |
| [getClass()](#getClass--) |  |
| [getConvertDateTimeData()](#getConvertDateTimeData--) | Gets or sets a value that indicates whether the string in text file is converted to date data. |
| [getConvertNumericData()](#getConvertNumericData--) | Gets or sets a value that indicates whether the string in text file is converted to numeric data. |
| [getDefaultStyleSettings()](#getDefaultStyleSettings--) | Gets the default style settings for initializing styles of the workbook |
| [getEncoding()](#getEncoding--) | Gets and sets the default encoding. |
| [getFontConfigs()](#getFontConfigs--) | Gets and sets individual font configs. |
| [getIgnoreNotPrinted()](#getIgnoreNotPrinted--) | Ignore the data which are not printed if directly printing the file Only for xlsx file. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Gets and sets the interrupt monitor. |
| [getKeepPrecision()](#getKeepPrecision--) | Indicates whether not parsing a string value if the length is 15. |
| [getKeepUnparsedData()](#getKeepUnparsedData--) | Whether keep the unparsed data in memory for the Workbook when it is loaded from template file. |
| [getLanguageCode()](#getLanguageCode--) | Gets or sets the user interface language of the Workbook version based on CountryCode that has saved the file. |
| [getLightCellsDataHandler()](#getLightCellsDataHandler--) | The data handler for processing cells data when reading template file. |
| [getLoadFilter()](#getLoadFilter--) | The filter to denote how to load data. |
| [getLoadFormat()](#getLoadFormat--) | Gets the load format. |
| [getLoadStyleStrategy()](#getLoadStyleStrategy--) | Indicates the strategy to apply style for parsed values when converting string value to number or datetime. |
| [getLocale()](#getLocale--) | Gets and sets the Locale used for workbook at the time the file was loaded. |
| [getMemorySetting()](#getMemorySetting--) | Gets or sets the memory usage options. |
| [getParsingFormulaOnOpen()](#getParsingFormulaOnOpen--) | Indicates whether parsing the formula when reading the file. |
| [getParsingPivotCachedRecords()](#getParsingPivotCachedRecords--) | Indicates whether parsing pivot cached records when loading the file. |
| [getPassword()](#getPassword--) | Gets and set the password of the workbook. |
| [getRegion()](#getRegion--) | Gets or sets the system regional settings based on CountryCode at the time the file was loaded. |
| [getStandardFont()](#getStandardFont--) | Sets the default standard font name NOTE: This member is now obsolete. |
| [getStandardFontSize()](#getStandardFontSize--) | Sets the default standard font size. |
| [getWarningCallback()](#getWarningCallback--) | Gets or sets warning callback. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFilter(boolean value)](#setAutoFilter-boolean-) | Please see the getter of this property: [getAutoFilter()](../../com.aspose.cells/loadoptions\#getAutoFilter--) |
| [setAutoFitterOptions(AutoFitterOptions value)](#setAutoFitterOptions-com.aspose.cells.AutoFitterOptions-) | Please see the getter of this property: [getAutoFitterOptions()](../../com.aspose.cells/loadoptions\#getAutoFitterOptions--) |
| [setCheckDataValid(boolean value)](#setCheckDataValid-boolean-) | Please see the getter of this property: [getCheckDataValid()](../../com.aspose.cells/loadoptions\#getCheckDataValid--) |
| [setCheckExcelRestriction(boolean value)](#setCheckExcelRestriction-boolean-) | Please see the getter of this property: [getCheckExcelRestriction()](../../com.aspose.cells/loadoptions\#getCheckExcelRestriction--) |
| [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Please see the getter of this property: @CREF245\_ |
| [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Please see the getter of this property: @CREF244\_ |
| [setEncoding(Encoding value)](#setEncoding-com.aspose.cells.Encoding-) | Please see the getter of this property: @CREF242\_ |
| [setFontConfigs(IndividualFontConfigs value)](#setFontConfigs-com.aspose.cells.IndividualFontConfigs-) | Please see the getter of this property: [getFontConfigs()](../../com.aspose.cells/loadoptions\#getFontConfigs--) |
| [setIgnoreNotPrinted(boolean value)](#setIgnoreNotPrinted-boolean-) | Please see the getter of this property: [getIgnoreNotPrinted()](../../com.aspose.cells/loadoptions\#getIgnoreNotPrinted--) |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.cells.AbstractInterruptMonitor-) | Please see the getter of this property: [getInterruptMonitor()](../../com.aspose.cells/loadoptions\#getInterruptMonitor--) |
| [setKeepPrecision(boolean value)](#setKeepPrecision-boolean-) | Please see the getter of this property: @CREF246\_ |
| [setKeepUnparsedData(boolean value)](#setKeepUnparsedData-boolean-) | Please see the getter of this property: [getKeepUnparsedData()](../../com.aspose.cells/loadoptions\#getKeepUnparsedData--) |
| [setLanguageCode(int value)](#setLanguageCode-int-) | Please see the getter of this property: [getLanguageCode()](../../com.aspose.cells/loadoptions\#getLanguageCode--) |
| [setLightCellsDataHandler(LightCellsDataHandler value)](#setLightCellsDataHandler-com.aspose.cells.LightCellsDataHandler-) | Please see the getter of this property: [getLightCellsDataHandler()](../../com.aspose.cells/loadoptions\#getLightCellsDataHandler--) |
| [setLoadFilter(LoadFilter value)](#setLoadFilter-com.aspose.cells.LoadFilter-) | Please see the getter of this property: [getLoadFilter()](../../com.aspose.cells/loadoptions\#getLoadFilter--) |
| [setLoadStyleStrategy(int value)](#setLoadStyleStrategy-int-) | Please see the getter of this property: @CREF243\_ |
| [setLocale(Locale value)](#setLocale-java.util.Locale-) | Please see the getter of this property: [getLocale()](../../com.aspose.cells/loadoptions\#getLocale--) |
| [setMemorySetting(int value)](#setMemorySetting-int-) | Please see the getter of this property: [getMemorySetting()](../../com.aspose.cells/loadoptions\#getMemorySetting--) |
| [setPaperSize(int type)](#setPaperSize-int-) | Sets the default print paper size from default printer's setting. |
| [setParsingFormulaOnOpen(boolean value)](#setParsingFormulaOnOpen-boolean-) | Please see the getter of this property: [getParsingFormulaOnOpen()](../../com.aspose.cells/loadoptions\#getParsingFormulaOnOpen--) |
| [setParsingPivotCachedRecords(boolean value)](#setParsingPivotCachedRecords-boolean-) | Please see the getter of this property: [getParsingPivotCachedRecords()](../../com.aspose.cells/loadoptions\#getParsingPivotCachedRecords--) |
| [setPassword(String value)](#setPassword-java.lang.String-) | Please see the getter of this property: [getPassword()](../../com.aspose.cells/loadoptions\#getPassword--) |
| [setRegion(int value)](#setRegion-int-) | Please see the getter of this property: [getRegion()](../../com.aspose.cells/loadoptions\#getRegion--) |
| [setStandardFont(String value)](#setStandardFont-java.lang.String-) | Please see the getter of this property: [getStandardFont()](../../com.aspose.cells/loadoptions\#getStandardFont--) |
| [setStandardFontSize(double value)](#setStandardFontSize-double-) | Please see the getter of this property: [getStandardFontSize()](../../com.aspose.cells/loadoptions\#getStandardFontSize--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.cells.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AbstractTextLoadOptions() {#AbstractTextLoadOptions--}
```
public AbstractTextLoadOptions()
```


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
### getAutoFilter() {#getAutoFilter--}
```
public boolean getAutoFilter()
```


Indicates whether auto filtering the data when loading the files. Sometimes although autofilter is set, the corresponding rows is not hidden in the file. Now only works for SpreadSheetML file.

**Returns:**
boolean
### getAutoFitterOptions() {#getAutoFitterOptions--}
```
public AutoFitterOptions getAutoFitterOptions()
```


Gets and sets the auto fitter options Only for xlsx ,spreadsheetML file now.

**Returns:**
[AutoFitterOptions](../../com.aspose.cells/autofitteroptions)
### getCheckDataValid() {#getCheckDataValid--}
```
public boolean getCheckDataValid()
```


Check whether data is valid in the template file.

**Returns:**
boolean
### getCheckExcelRestriction() {#getCheckExcelRestriction--}
```
public boolean getCheckExcelRestriction()
```


Whether check restriction of excel file when user modify cells related objects. For example, excel does not allow inputting string value longer than 32K. When you input a value longer than 32K such as by Cell.PutValue(string), if this property is true, you will get an Exception. If this property is false, we will accept your input string value as the cell's value so that later you can output the complete string value for other file formats such as CSV. However, if you have set such kind of value that is invalid for excel file format, you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public boolean getConvertDateTimeData()
```


Gets or sets a value that indicates whether the string in text file is converted to date data.

**Returns:**
boolean
### getConvertNumericData() {#getConvertNumericData--}
```
public boolean getConvertNumericData()
```


Gets or sets a value that indicates whether the string in text file is converted to numeric data.

**Returns:**
boolean
### getDefaultStyleSettings() {#getDefaultStyleSettings--}
```
public DefaultStyleSettings getDefaultStyleSettings()
```


Gets the default style settings for initializing styles of the workbook

**Returns:**
[DefaultStyleSettings](../../com.aspose.cells/defaultstylesettings)
### getEncoding() {#getEncoding--}
```
public Encoding getEncoding()
```


Gets and sets the default encoding. Only applies for csv file.

**Returns:**
[Encoding](../../com.aspose.cells/encoding)
### getFontConfigs() {#getFontConfigs--}
```
public IndividualFontConfigs getFontConfigs()
```


Gets and sets individual font configs. Only works for the [Workbook](../../com.aspose.cells/workbook) which uses this [LoadOptions](../../com.aspose.cells/loadoptions) to load.

**Returns:**
[IndividualFontConfigs](../../com.aspose.cells/individualfontconfigs)
### getIgnoreNotPrinted() {#getIgnoreNotPrinted--}
```
public boolean getIgnoreNotPrinted()
```


Ignore the data which are not printed if directly printing the file Only for xlsx file.

**Returns:**
boolean
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


Gets and sets the interrupt monitor.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.cells/abstractinterruptmonitor)
### getKeepPrecision() {#getKeepPrecision--}
```
public boolean getKeepPrecision()
```


Indicates whether not parsing a string value if the length is 15.

**Returns:**
boolean
### getKeepUnparsedData() {#getKeepUnparsedData--}
```
public boolean getKeepUnparsedData()
```


Whether keep the unparsed data in memory for the Workbook when it is loaded from template file. Default is true. For scenarios that user only needs to read some contents from template file and does not need to save the workbook back, set this property as false may improve performance, especially when using it together with some kind of LoadFilter,

**Returns:**
boolean
### getLanguageCode() {#getLanguageCode--}
```
public int getLanguageCode()
```


Gets or sets the user interface language of the Workbook version based on CountryCode that has saved the file.

**Returns:**
int
### getLightCellsDataHandler() {#getLightCellsDataHandler--}
```
public LightCellsDataHandler getLightCellsDataHandler()
```


The data handler for processing cells data when reading template file.

**Returns:**
[LightCellsDataHandler](../../com.aspose.cells/lightcellsdatahandler)
### getLoadFilter() {#getLoadFilter--}
```
public LoadFilter getLoadFilter()
```


The filter to denote how to load data.

**Returns:**
[LoadFilter](../../com.aspose.cells/loadfilter)
### getLoadFormat() {#getLoadFormat--}
```
public int getLoadFormat()
```


Gets the load format.

**Returns:**
int
### getLoadStyleStrategy() {#getLoadStyleStrategy--}
```
public int getLoadStyleStrategy()
```


Indicates the strategy to apply style for parsed values when converting string value to number or datetime.

**Returns:**
int
### getLocale() {#getLocale--}
```
public Locale getLocale()
```


Gets and sets the Locale used for workbook at the time the file was loaded.

**Returns:**
java.util.Locale
### getMemorySetting() {#getMemorySetting--}
```
public int getMemorySetting()
```


Gets or sets the memory usage options.

**Returns:**
int
### getParsingFormulaOnOpen() {#getParsingFormulaOnOpen--}
```
public boolean getParsingFormulaOnOpen()
```


Indicates whether parsing the formula when reading the file. Only applies for Excel Xlsx, Xltx, Xltm and Xlsm file because the formulas in the files are stored with a string formula.

**Returns:**
boolean
### getParsingPivotCachedRecords() {#getParsingPivotCachedRecords--}
```
public boolean getParsingPivotCachedRecords()
```


Indicates whether parsing pivot cached records when loading the file. The default value is false. Only applies for Excel Xlsx, Xltx, Xltm , Xlsm and xlsb file

**Returns:**
boolean
### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets and set the password of the workbook.

**Returns:**
java.lang.String
### getRegion() {#getRegion--}
```
public int getRegion()
```


Gets or sets the system regional settings based on CountryCode at the time the file was loaded. If you do not want to use the region saved in the file, please reset it after reading the file.

**Returns:**
int
### getStandardFont() {#getStandardFont--}
```
public String getStandardFont()
```


Sets the default standard font name NOTE: This member is now obsolete. Instead, please use DefaultStyleSettings. This property will be removed 12 months later since March 2022. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
java.lang.String
### getStandardFontSize() {#getStandardFontSize--}
```
public double getStandardFontSize()
```


Sets the default standard font size. NOTE: This member is now obsolete. Instead, please use DefaultStyleSettings. This property will be removed 12 months later since March 2022. Aspose apologizes for any inconvenience you may have experienced.

**Returns:**
double
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


Gets or sets warning callback.

**Returns:**
[IWarningCallback](../../com.aspose.cells/iwarningcallback)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoFilter(boolean value) {#setAutoFilter-boolean-}
```
public void setAutoFilter(boolean value)
```


Please see the getter of this property: [getAutoFilter()](../../com.aspose.cells/loadoptions\#getAutoFilter--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAutoFitterOptions(AutoFitterOptions value) {#setAutoFitterOptions-com.aspose.cells.AutoFitterOptions-}
```
public void setAutoFitterOptions(AutoFitterOptions value)
```


Please see the getter of this property: [getAutoFitterOptions()](../../com.aspose.cells/loadoptions\#getAutoFitterOptions--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AutoFitterOptions](../../com.aspose.cells/autofitteroptions) |  |

### setCheckDataValid(boolean value) {#setCheckDataValid-boolean-}
```
public void setCheckDataValid(boolean value)
```


Please see the getter of this property: [getCheckDataValid()](../../com.aspose.cells/loadoptions\#getCheckDataValid--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setCheckExcelRestriction(boolean value) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean value)
```


Please see the getter of this property: [getCheckExcelRestriction()](../../com.aspose.cells/loadoptions\#getCheckExcelRestriction--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public void setConvertDateTimeData(boolean value)
```


Please see the getter of this property: @CREF245\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public void setConvertNumericData(boolean value)
```


Please see the getter of this property: @CREF244\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setEncoding(Encoding value) {#setEncoding-com.aspose.cells.Encoding-}
```
public void setEncoding(Encoding value)
```


Please see the getter of this property: @CREF242\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Encoding](../../com.aspose.cells/encoding) |  |

### setFontConfigs(IndividualFontConfigs value) {#setFontConfigs-com.aspose.cells.IndividualFontConfigs-}
```
public void setFontConfigs(IndividualFontConfigs value)
```


Please see the getter of this property: [getFontConfigs()](../../com.aspose.cells/loadoptions\#getFontConfigs--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IndividualFontConfigs](../../com.aspose.cells/individualfontconfigs) |  |

### setIgnoreNotPrinted(boolean value) {#setIgnoreNotPrinted-boolean-}
```
public void setIgnoreNotPrinted(boolean value)
```


Please see the getter of this property: [getIgnoreNotPrinted()](../../com.aspose.cells/loadoptions\#getIgnoreNotPrinted--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.cells.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Please see the getter of this property: [getInterruptMonitor()](../../com.aspose.cells/loadoptions\#getInterruptMonitor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.cells/abstractinterruptmonitor) |  |

### setKeepPrecision(boolean value) {#setKeepPrecision-boolean-}
```
public void setKeepPrecision(boolean value)
```


Please see the getter of this property: @CREF246\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setKeepUnparsedData(boolean value) {#setKeepUnparsedData-boolean-}
```
public void setKeepUnparsedData(boolean value)
```


Please see the getter of this property: [getKeepUnparsedData()](../../com.aspose.cells/loadoptions\#getKeepUnparsedData--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setLanguageCode(int value) {#setLanguageCode-int-}
```
public void setLanguageCode(int value)
```


Please see the getter of this property: [getLanguageCode()](../../com.aspose.cells/loadoptions\#getLanguageCode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLightCellsDataHandler(LightCellsDataHandler value) {#setLightCellsDataHandler-com.aspose.cells.LightCellsDataHandler-}
```
public void setLightCellsDataHandler(LightCellsDataHandler value)
```


Please see the getter of this property: [getLightCellsDataHandler()](../../com.aspose.cells/loadoptions\#getLightCellsDataHandler--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LightCellsDataHandler](../../com.aspose.cells/lightcellsdatahandler) |  |

### setLoadFilter(LoadFilter value) {#setLoadFilter-com.aspose.cells.LoadFilter-}
```
public void setLoadFilter(LoadFilter value)
```


Please see the getter of this property: [getLoadFilter()](../../com.aspose.cells/loadoptions\#getLoadFilter--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LoadFilter](../../com.aspose.cells/loadfilter) |  |

### setLoadStyleStrategy(int value) {#setLoadStyleStrategy-int-}
```
public void setLoadStyleStrategy(int value)
```


Please see the getter of this property: @CREF243\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public void setLocale(Locale value)
```


Please see the getter of this property: [getLocale()](../../com.aspose.cells/loadoptions\#getLocale--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### setMemorySetting(int value) {#setMemorySetting-int-}
```
public void setMemorySetting(int value)
```


Please see the getter of this property: [getMemorySetting()](../../com.aspose.cells/loadoptions\#getMemorySetting--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPaperSize(int type) {#setPaperSize-int-}
```
public void setPaperSize(int type)
```


Sets the default print paper size from default printer's setting. If there is no setting about paper size,MS Excel will use default printer's setting.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The default paper size. |

### setParsingFormulaOnOpen(boolean value) {#setParsingFormulaOnOpen-boolean-}
```
public void setParsingFormulaOnOpen(boolean value)
```


Please see the getter of this property: [getParsingFormulaOnOpen()](../../com.aspose.cells/loadoptions\#getParsingFormulaOnOpen--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setParsingPivotCachedRecords(boolean value) {#setParsingPivotCachedRecords-boolean-}
```
public void setParsingPivotCachedRecords(boolean value)
```


Please see the getter of this property: [getParsingPivotCachedRecords()](../../com.aspose.cells/loadoptions\#getParsingPivotCachedRecords--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Please see the getter of this property: [getPassword()](../../com.aspose.cells/loadoptions\#getPassword--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRegion(int value) {#setRegion-int-}
```
public void setRegion(int value)
```


Please see the getter of this property: [getRegion()](../../com.aspose.cells/loadoptions\#getRegion--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStandardFont(String value) {#setStandardFont-java.lang.String-}
```
public void setStandardFont(String value)
```


Please see the getter of this property: [getStandardFont()](../../com.aspose.cells/loadoptions\#getStandardFont--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStandardFontSize(double value) {#setStandardFontSize-double-}
```
public void setStandardFontSize(double value)
```


Please see the getter of this property: [getStandardFontSize()](../../com.aspose.cells/loadoptions\#getStandardFontSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.cells.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.cells/iwarningcallback) |  |

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
