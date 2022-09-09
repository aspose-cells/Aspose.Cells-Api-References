---
title: Protection
second_title: Aspose.Cells لمرجع .NET API
description: يمثل الأنواع المختلفة لخيارات الحماية المتاحة لورقة العمل.
type: docs
weight: 4910
url: /ar/net/aspose.cells/protection/
---
## Protection class

يمثل الأنواع المختلفة لخيارات الحماية المتاحة لورقة العمل.

```csharp
public class Protection
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllowDeletingColumn](../../aspose.cells/protection/allowdeletingcolumn) { get; set; } | يمثل ما إذا كان حذف الأعمدة مسموحًا به في ورقة العمل المحمية. |
| [AllowDeletingRow](../../aspose.cells/protection/allowdeletingrow) { get; set; } | يمثل ما إذا كان حذف الصفوف مسموحًا به في ورقة عمل محمية. |
| [AllowEditingContent](../../aspose.cells/protection/alloweditingcontent) { get; set; } | يمثل ما إذا كان يُسمح للمستخدم بتحرير محتويات الخلايا المقفلة في ورقة عمل محمية. |
| [AllowEditingObject](../../aspose.cells/protection/alloweditingobject) { get; set; } | يمثل ما إذا كان يُسمح للمستخدم بمعالجة الكائنات الرسومية في ورقة عمل محمية. |
| [AllowEditingScenario](../../aspose.cells/protection/alloweditingscenario) { get; set; } | يمثل ما إذا كان يُسمح للمستخدم بتحرير السيناريوهات في ورقة عمل محمية. |
| [AllowFiltering](../../aspose.cells/protection/allowfiltering) { get; set; } | يمثل ما إذا كان مسموحًا للمستخدم باستخدام عامل التصفية التلقائي الذي تم إنشاؤه قبل حماية الورقة. |
| [AllowFormattingCell](../../aspose.cells/protection/allowformattingcell) { get; set; } | يمثل ما إذا كان تنسيق الخلايا مسموحًا به في ورقة عمل محمية. |
| [AllowFormattingColumn](../../aspose.cells/protection/allowformattingcolumn) { get; set; } | يمثل ما إذا كان تنسيق الأعمدة مسموحًا به في ورقة عمل محمية |
| [AllowFormattingRow](../../aspose.cells/protection/allowformattingrow) { get; set; } | يمثل ما إذا كان تنسيق الصفوف مسموحًا به في ورقة عمل محمية |
| [AllowInsertingColumn](../../aspose.cells/protection/allowinsertingcolumn) { get; set; } | يمثل ما إذا كان إدخال الأعمدة مسموحًا به في ورقة عمل محمية |
| [AllowInsertingHyperlink](../../aspose.cells/protection/allowinsertinghyperlink) { get; set; } | يمثل ما إذا كان إدخال الارتباطات التشعبية مسموحًا به في ورقة عمل محمية |
| [AllowInsertingRow](../../aspose.cells/protection/allowinsertingrow) { get; set; } | يمثل ما إذا كان إدخال الصفوف مسموحًا به في ورقة عمل محمية |
| [AllowSelectingLockedCell](../../aspose.cells/protection/allowselectinglockedcell) { get; set; } | يمثل ما إذا كان يُسمح للمستخدم بتحديد الخلايا المقفلة في ورقة عمل محمية. |
| [AllowSelectingUnlockedCell](../../aspose.cells/protection/allowselectingunlockedcell) { get; set; } | يمثل ما إذا كان يُسمح للمستخدم بتحديد خلايا غير مؤمنة في ورقة عمل محمية. |
| [AllowSorting](../../aspose.cells/protection/allowsorting) { get; set; } | يمثل ما إذا كان خيار الفرز مسموحًا به في ورقة عمل محمية. |
| [AllowUsingPivotTable](../../aspose.cells/protection/allowusingpivottable) { get; set; } | يمثل ما إذا كان يُسمح للمستخدم بمعالجة الجداول المحورية في ورقة عمل محمية. |
| [IsProtectedWithPassword](../../aspose.cells/protection/isprotectedwithpassword) { get; } | يشير إلى ما إذا كانت أوراق العمل محمية بكلمة مرور. |
| [Password](../../aspose.cells/protection/password) { get; set; } | يمثل كلمة المرور لحماية ورقة العمل. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Copy](../../aspose.cells/protection/copy)(Protection) | معلومات حماية النسخ . |
| [GetPasswordHash](../../aspose.cells/protection/getpasswordhash)() | يحصل على تجزئة كلمة المرور الحالية. |
| [VerifyPassword](../../aspose.cells/protection/verifypassword)(string) | التحقق من كلمة المرور . |

### أمثلة

```csharp

[C#]
// إنشاء كائن مصنف
Workbook workbook = new Workbook();

Worksheet worksheet = workbook.Worksheets[0];
// السماح للمستخدمين بتحديد الخلايا المؤمنة من ورقة العمل
worksheet.Protection.AllowSelectingLockedCell = true;
// السماح للمستخدمين بتحديد خلايا غير مؤمنة من ورقة العمل
worksheet.Protection.AllowSelectingUnlockedCell = true;  

[Visual Basic]

'إنشاء كائن مصنف
Dim workbook As Workbook = New Workbook()
Dim worksheet As Worksheet = workbook.Worksheets(0)
'السماح للمستخدمين بتحديد الخلايا المؤمنة من ورقة العمل
worksheet.Protection.AllowSelectingLockedCell = True
'السماح للمستخدمين بتحديد الخلايا غير المؤمنة من ورقة العمل
worksheet.Protection.AllowSelectingUnlockedCell = True
```

### أنظر أيضا

* مساحة الاسم [Aspose.Cells](../../aspose.cells)
* المجسم [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->