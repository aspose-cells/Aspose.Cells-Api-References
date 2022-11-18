---
title: PdfSecurityOptions
second_title: Aspose.Cells for Java API Reference
description: Settings of pdf when converting excel to pdf PDF/A does not allow security setting.
type: docs
weight: 389
url: /java/com.aspose.cells/pdfsecurityoptions/
---

**Inheritance:**
java.lang.Object
```
public class PdfSecurityOptions
```

Settings of pdf when converting excel to pdf, PDF/A does not allow security setting.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSecurityOptions()](#PdfSecurityOptions--) | The constructor of PdfSecurityOptions |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccessibilityExtractContent()](#getAccessibilityExtractContent--) | Permission to copy or extract content (in support of accessibility to disabled users or for other purposes). |
| [getAnnotationsPermission()](#getAnnotationsPermission--) | Permission to comment on the document. |
| [getAssembleDocumentPermission()](#getAssembleDocumentPermission--) | Permission to insert, rotate, or delete pages and create bookmarks or thumbnail images even if ModifyDocumentPermission is not set. |
| [getClass()](#getClass--) |  |
| [getExtractContentPermission()](#getExtractContentPermission--) | Permission to copy or extract content. |
| [getExtractContentPermissionObsolete()](#getExtractContentPermissionObsolete--) | Permission to copy or extract content Obsoleted according to PDF reference. |
| [getFillFormsPermission()](#getFillFormsPermission--) | Permission to fill the form fields. |
| [getFullQualityPrintPermission()](#getFullQualityPrintPermission--) | Permission to print in high quality. |
| [getModifyDocumentPermission()](#getModifyDocumentPermission--) | Permission to modify pdf document |
| [getOwnerPassword()](#getOwnerPassword--) | Gets or sets the owner password of the document |
| [getPrintPermission()](#getPrintPermission--) | Permission to print pdf document |
| [getUserPassword()](#getUserPassword--) | Gets or sets the user password |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccessibilityExtractContent(boolean value)](#setAccessibilityExtractContent-boolean-) | Please see the getter of this property: [getAccessibilityExtractContent()](../../com.aspose.cells/pdfsecurityoptions\#getAccessibilityExtractContent--) |
| [setAnnotationsPermission(boolean value)](#setAnnotationsPermission-boolean-) | Please see the getter of this property: [getAnnotationsPermission()](../../com.aspose.cells/pdfsecurityoptions\#getAnnotationsPermission--) |
| [setAssembleDocumentPermission(boolean value)](#setAssembleDocumentPermission-boolean-) | Please see the getter of this property: [getAssembleDocumentPermission()](../../com.aspose.cells/pdfsecurityoptions\#getAssembleDocumentPermission--) |
| [setExtractContentPermission(boolean value)](#setExtractContentPermission-boolean-) | Please see the getter of this property: [getExtractContentPermission()](../../com.aspose.cells/pdfsecurityoptions\#getExtractContentPermission--) |
| [setExtractContentPermissionObsolete(boolean value)](#setExtractContentPermissionObsolete-boolean-) | Please see the getter of this property: [getExtractContentPermissionObsolete()](../../com.aspose.cells/pdfsecurityoptions\#getExtractContentPermissionObsolete--) |
| [setFillFormsPermission(boolean value)](#setFillFormsPermission-boolean-) | Please see the getter of this property: [getFillFormsPermission()](../../com.aspose.cells/pdfsecurityoptions\#getFillFormsPermission--) |
| [setFullQualityPrintPermission(boolean value)](#setFullQualityPrintPermission-boolean-) | Please see the getter of this property: [getFullQualityPrintPermission()](../../com.aspose.cells/pdfsecurityoptions\#getFullQualityPrintPermission--) |
| [setModifyDocumentPermission(boolean value)](#setModifyDocumentPermission-boolean-) | Please see the getter of this property: [getModifyDocumentPermission()](../../com.aspose.cells/pdfsecurityoptions\#getModifyDocumentPermission--) |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Please see the getter of this property: [getOwnerPassword()](../../com.aspose.cells/pdfsecurityoptions\#getOwnerPassword--) |
| [setPrintPermission(boolean value)](#setPrintPermission-boolean-) | Please see the getter of this property: [getPrintPermission()](../../com.aspose.cells/pdfsecurityoptions\#getPrintPermission--) |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | Please see the getter of this property: [getUserPassword()](../../com.aspose.cells/pdfsecurityoptions\#getUserPassword--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSecurityOptions() {#PdfSecurityOptions--}
```
public PdfSecurityOptions()
```


The constructor of PdfSecurityOptions

```
Workbook wb = new Workbook();
         wb.getWorksheets().get(0).getCells().get("A1").setValue("Aspose");
 
         PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();
 
 
         PdfSecurityOptions pdfSecurityOptions = new PdfSecurityOptions();
 
         //set owner password
         pdfSecurityOptions.setOwnerPassword("YourOwnerPassword");
 
         //set user password
         pdfSecurityOptions.setUserPassword("YourUserPassword");
 
         //set print permisson
         pdfSecurityOptions.setPrintPermission(true);
 
         //set high resolution for print
         pdfSecurityOptions.setFullQualityPrintPermission(true);
 
 
         pdfSaveOptions.setSecurityOptions(pdfSecurityOptions);
 
         wb.save("output.pdf", pdfSaveOptions);
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
### getAccessibilityExtractContent() {#getAccessibilityExtractContent--}
```
public boolean getAccessibilityExtractContent()
```


Permission to copy or extract content (in support of accessibility to disabled users or for other purposes).

**Returns:**
boolean
### getAnnotationsPermission() {#getAnnotationsPermission--}
```
public boolean getAnnotationsPermission()
```


Permission to comment on the document.

**Returns:**
boolean
### getAssembleDocumentPermission() {#getAssembleDocumentPermission--}
```
public boolean getAssembleDocumentPermission()
```


Permission to insert, rotate, or delete pages and create bookmarks or thumbnail images even if ModifyDocumentPermission is not set.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtractContentPermission() {#getExtractContentPermission--}
```
public boolean getExtractContentPermission()
```


Permission to copy or extract content.

**Returns:**
boolean
### getExtractContentPermissionObsolete() {#getExtractContentPermissionObsolete--}
```
public boolean getExtractContentPermissionObsolete()
```


Permission to copy or extract content Obsoleted according to PDF reference.

**Returns:**
boolean
### getFillFormsPermission() {#getFillFormsPermission--}
```
public boolean getFillFormsPermission()
```


Permission to fill the form fields.

**Returns:**
boolean
### getFullQualityPrintPermission() {#getFullQualityPrintPermission--}
```
public boolean getFullQualityPrintPermission()
```


Permission to print in high quality.

**Returns:**
boolean
### getModifyDocumentPermission() {#getModifyDocumentPermission--}
```
public boolean getModifyDocumentPermission()
```


Permission to modify pdf document

**Returns:**
boolean
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


Gets or sets the owner password of the document

**Returns:**
java.lang.String
### getPrintPermission() {#getPrintPermission--}
```
public boolean getPrintPermission()
```


Permission to print pdf document

**Returns:**
boolean
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


Gets or sets the user password

**Returns:**
java.lang.String
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




### setAccessibilityExtractContent(boolean value) {#setAccessibilityExtractContent-boolean-}
```
public void setAccessibilityExtractContent(boolean value)
```


Please see the getter of this property: [getAccessibilityExtractContent()](../../com.aspose.cells/pdfsecurityoptions\#getAccessibilityExtractContent--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAnnotationsPermission(boolean value) {#setAnnotationsPermission-boolean-}
```
public void setAnnotationsPermission(boolean value)
```


Please see the getter of this property: [getAnnotationsPermission()](../../com.aspose.cells/pdfsecurityoptions\#getAnnotationsPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAssembleDocumentPermission(boolean value) {#setAssembleDocumentPermission-boolean-}
```
public void setAssembleDocumentPermission(boolean value)
```


Please see the getter of this property: [getAssembleDocumentPermission()](../../com.aspose.cells/pdfsecurityoptions\#getAssembleDocumentPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExtractContentPermission(boolean value) {#setExtractContentPermission-boolean-}
```
public void setExtractContentPermission(boolean value)
```


Please see the getter of this property: [getExtractContentPermission()](../../com.aspose.cells/pdfsecurityoptions\#getExtractContentPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExtractContentPermissionObsolete(boolean value) {#setExtractContentPermissionObsolete-boolean-}
```
public void setExtractContentPermissionObsolete(boolean value)
```


Please see the getter of this property: [getExtractContentPermissionObsolete()](../../com.aspose.cells/pdfsecurityoptions\#getExtractContentPermissionObsolete--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFillFormsPermission(boolean value) {#setFillFormsPermission-boolean-}
```
public void setFillFormsPermission(boolean value)
```


Please see the getter of this property: [getFillFormsPermission()](../../com.aspose.cells/pdfsecurityoptions\#getFillFormsPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFullQualityPrintPermission(boolean value) {#setFullQualityPrintPermission-boolean-}
```
public void setFullQualityPrintPermission(boolean value)
```


Please see the getter of this property: [getFullQualityPrintPermission()](../../com.aspose.cells/pdfsecurityoptions\#getFullQualityPrintPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setModifyDocumentPermission(boolean value) {#setModifyDocumentPermission-boolean-}
```
public void setModifyDocumentPermission(boolean value)
```


Please see the getter of this property: [getModifyDocumentPermission()](../../com.aspose.cells/pdfsecurityoptions\#getModifyDocumentPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


Please see the getter of this property: [getOwnerPassword()](../../com.aspose.cells/pdfsecurityoptions\#getOwnerPassword--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPrintPermission(boolean value) {#setPrintPermission-boolean-}
```
public void setPrintPermission(boolean value)
```


Please see the getter of this property: [getPrintPermission()](../../com.aspose.cells/pdfsecurityoptions\#getPrintPermission--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


Please see the getter of this property: [getUserPassword()](../../com.aspose.cells/pdfsecurityoptions\#getUserPassword--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
