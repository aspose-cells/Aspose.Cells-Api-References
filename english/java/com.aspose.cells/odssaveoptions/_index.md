---
title: OdsSaveOptions
second_title: Aspose.Cells for Java API Reference
description: Represents the options of saving ods file.
type: docs
weight: 358
url: /java/com.aspose.cells/odssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.cells.SaveOptions](../../com.aspose.cells/saveoptions)
```
public class OdsSaveOptions extends SaveOptions
```

Represents the options of saving ods file.
## Constructors

| Constructor | Description |
| --- | --- |
| [OdsSaveOptions()](#OdsSaveOptions--) | Creates the options of saving ods file. |
| [OdsSaveOptions(int saveFormat)](#OdsSaveOptions-int-) | Creates the options of saving ods file. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCachedFileFolder()](#getCachedFileFolder--) | The cached file folder is used to store some large data. |
| [getClass()](#getClass--) |  |
| [getClearData()](#getClearData--) | Make the workbook empty after saving the file. |
| [getCreateDirectory()](#getCreateDirectory--) | If true and the directory does not exist, the directory will be automatically created before saving the file. |
| [getGeneratorType()](#getGeneratorType--) | Gets and sets the generator of the ods file. |
| [getMergeAreas()](#getMergeAreas--) | Indicates whether merge the areas of conditional formatting and validation before saving the file. |
| [getRefreshChartCache()](#getRefreshChartCache--) | Indicates whether refreshing chart cache data |
| [getSaveFormat()](#getSaveFormat--) | Gets the save file format. |
| [getSortExternalNames()](#getSortExternalNames--) | Indicates whether sorting external defined names before saving file. |
| [getSortNames()](#getSortNames--) | Indicates whether sorting defined names before saving file. |
| [getUpdateSmartArt()](#getUpdateSmartArt--) | Indicates whether updating smart art setting. |
| [getValidateMergedAreas()](#getValidateMergedAreas--) | Indicates whether validate merged cells before saving the file. |
| [getWarningCallback()](#getWarningCallback--) | Gets or sets warning callback. |
| [hashCode()](#hashCode--) |  |
| [isStrictSchema11()](#isStrictSchema11--) | Indicates whether the ods file should be saved as ODF format version 1.1. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCachedFileFolder(String value)](#setCachedFileFolder-java.lang.String-) | Please see the getter of this property: @CREF1852\_ |
| [setClearData(boolean value)](#setClearData-boolean-) | Please see the getter of this property: @CREF1851\_ |
| [setCreateDirectory(boolean value)](#setCreateDirectory-boolean-) | Please see the getter of this property: @CREF1855\_ |
| [setGeneratorType(int value)](#setGeneratorType-int-) | Please see the getter of this property: @CREF1232\_ |
| [setMergeAreas(boolean value)](#setMergeAreas-boolean-) | Please see the getter of this property: @CREF1854\_ |
| [setRefreshChartCache(boolean value)](#setRefreshChartCache-boolean-) | Please see the getter of this property: @CREF1858\_ |
| [setSortExternalNames(boolean value)](#setSortExternalNames-boolean-) | Please see the getter of this property: @CREF1857\_ |
| [setSortNames(boolean value)](#setSortNames-boolean-) | Please see the getter of this property: @CREF1856\_ |
| [setStrictSchema11(boolean value)](#setStrictSchema11-boolean-) | Please see the getter of this property: @CREF1233\_ |
| [setUpdateSmartArt(boolean value)](#setUpdateSmartArt-boolean-) | Please see the getter of this property: @CREF1860\_ |
| [setValidateMergedAreas(boolean value)](#setValidateMergedAreas-boolean-) | Please see the getter of this property: @CREF1853\_ |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.cells.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OdsSaveOptions() {#OdsSaveOptions--}
```
public OdsSaveOptions()
```


Creates the options of saving ods file.

### OdsSaveOptions(int saveFormat) {#OdsSaveOptions-int-}
```
public OdsSaveOptions(int saveFormat)
```


Creates the options of saving ods file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int |  |

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
### getCachedFileFolder() {#getCachedFileFolder--}
```
public String getCachedFileFolder()
```


The cached file folder is used to store some large data.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClearData() {#getClearData--}
```
public boolean getClearData()
```


Make the workbook empty after saving the file.

**Returns:**
boolean
### getCreateDirectory() {#getCreateDirectory--}
```
public boolean getCreateDirectory()
```


If true and the directory does not exist, the directory will be automatically created before saving the file. The default value is false.

**Returns:**
boolean
### getGeneratorType() {#getGeneratorType--}
```
public int getGeneratorType()
```


Gets and sets the generator of the ods file.

**Returns:**
int
### getMergeAreas() {#getMergeAreas--}
```
public boolean getMergeAreas()
```


Indicates whether merge the areas of conditional formatting and validation before saving the file. The default value is false.

**Returns:**
boolean
### getRefreshChartCache() {#getRefreshChartCache--}
```
public boolean getRefreshChartCache()
```


Indicates whether refreshing chart cache data

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Gets the save file format.

**Returns:**
int
### getSortExternalNames() {#getSortExternalNames--}
```
public boolean getSortExternalNames()
```


Indicates whether sorting external defined names before saving file.

**Returns:**
boolean
### getSortNames() {#getSortNames--}
```
public boolean getSortNames()
```


Indicates whether sorting defined names before saving file.

**Returns:**
boolean
### getUpdateSmartArt() {#getUpdateSmartArt--}
```
public boolean getUpdateSmartArt()
```


Indicates whether updating smart art setting. The default value is false. Only effects after calling Shape.GetResultOfSmartArt() method and the cached shapes exist in the template file.

**Returns:**
boolean
### getValidateMergedAreas() {#getValidateMergedAreas--}
```
public boolean getValidateMergedAreas()
```


Indicates whether validate merged cells before saving the file. The default value is false.

**Returns:**
boolean
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
### isStrictSchema11() {#isStrictSchema11--}
```
public boolean isStrictSchema11()
```


Indicates whether the ods file should be saved as ODF format version 1.1. Default is false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCachedFileFolder(String value) {#setCachedFileFolder-java.lang.String-}
```
public void setCachedFileFolder(String value)
```


Please see the getter of this property: @CREF1852\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setClearData(boolean value) {#setClearData-boolean-}
```
public void setClearData(boolean value)
```


Please see the getter of this property: @CREF1851\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setCreateDirectory(boolean value) {#setCreateDirectory-boolean-}
```
public void setCreateDirectory(boolean value)
```


Please see the getter of this property: @CREF1855\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGeneratorType(int value) {#setGeneratorType-int-}
```
public void setGeneratorType(int value)
```


Please see the getter of this property: @CREF1232\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMergeAreas(boolean value) {#setMergeAreas-boolean-}
```
public void setMergeAreas(boolean value)
```


Please see the getter of this property: @CREF1854\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRefreshChartCache(boolean value) {#setRefreshChartCache-boolean-}
```
public void setRefreshChartCache(boolean value)
```


Please see the getter of this property: @CREF1858\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSortExternalNames(boolean value) {#setSortExternalNames-boolean-}
```
public void setSortExternalNames(boolean value)
```


Please see the getter of this property: @CREF1857\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSortNames(boolean value) {#setSortNames-boolean-}
```
public void setSortNames(boolean value)
```


Please see the getter of this property: @CREF1856\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStrictSchema11(boolean value) {#setStrictSchema11-boolean-}
```
public void setStrictSchema11(boolean value)
```


Please see the getter of this property: @CREF1233\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUpdateSmartArt(boolean value) {#setUpdateSmartArt-boolean-}
```
public void setUpdateSmartArt(boolean value)
```


Please see the getter of this property: @CREF1860\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setValidateMergedAreas(boolean value) {#setValidateMergedAreas-boolean-}
```
public void setValidateMergedAreas(boolean value)
```


Please see the getter of this property: @CREF1853\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
