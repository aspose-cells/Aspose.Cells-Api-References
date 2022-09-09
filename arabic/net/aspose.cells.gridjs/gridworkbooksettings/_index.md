---
title: GridWorkbookSettings
second_title: Aspose.Cells لمرجع .NET API
description: يمثل إعدادات المصنف.
type: docs
weight: 110
url: /ar/net/aspose.cells.gridjs/gridworkbooksettings/
---
## GridWorkbookSettings class

يمثل إعدادات المصنف.

```csharp
public class GridWorkbookSettings
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GridWorkbookSettings](gridworkbooksettings)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Author](../../aspose.cells.gridjs/gridworkbooksettings/author) { get; set; } | الحصول على كاتب الملف وتعيينه. |
| [CheckCustomNumberFormat](../../aspose.cells.gridjs/gridworkbooksettings/checkcustomnumberformat) { get; set; } | يشير إلى ما إذا كان التحقق من تنسيق الأرقام المخصص عند تعيين Style.Custom. |
| [CreateCalcChain](../../aspose.cells.gridjs/gridworkbooksettings/createcalcchain) { get; set; } | يشير إلى ما إذا كان سيتم إنشاء سلسلة صيغ محسوبة. الافتراضي هو خطأ. |
| [Date1904](../../aspose.cells.gridjs/gridworkbooksettings/date1904) { get; set; } | الحصول على أو تعيين قيمة تمثل ما إذا كان المصنف يستخدم نظام التاريخ 1904. |
| [EnableMacros](../../aspose.cells.gridjs/gridworkbooksettings/enablemacros) { get; set; } | تمكين وحدات الماكرو ؛ تعمل الآن فقط عند نسخ ورقة عمل إلى ورقة عمل أخرى في مصنف. |
| [ForceFullCalculate](../../aspose.cells.gridjs/gridworkbooksettings/forcefullcalculate) { get; set; } | يشير إلى ما إذا كان يتم إجراء الحساب بالكامل في كل مرة يتم فيها تشغيل عملية حسابية. |
| [Iteration](../../aspose.cells.gridjs/gridworkbooksettings/iteration) { get; set; } | يشير إلى ما إذا كان سيتم استخدام التكرار لحل المراجع الدائرية. |
| [MaxIteration](../../aspose.cells.gridjs/gridworkbooksettings/maxiteration) { get; set; } | إرجاع أو تعيين الحد الأقصى لعدد التكرارات لحل مرجع معاد ، القيمة الافتراضية هي 100. |
| [PrecisionAsDisplayed](../../aspose.cells.gridjs/gridworkbooksettings/precisionasdisplayed) { get; set; } | صحيح إذا كانت العمليات الحسابية في هذا المصنف ستتم باستخدام دقة الأرقام فقط أثناء عرضها |
| [ReCalculateOnOpen](../../aspose.cells.gridjs/gridworkbooksettings/recalculateonopen) { get; set; } | يشير إلى ما إذا كان سيتم إعادة حساب جميع الصيغ عند فتح الملف. |

### أمثلة

```csharp
[C#]

GridJsWorkbook g = new GridJsWorkbook();

GridWorkbookSettings gsettings = new GridWorkbookSettings();
g.Settings=gsettings;

// قم بعملك

[Visual Basic]
Dim g as GridJsWorkbook = new GridJsWorkbook()

Dim gsettings as GridWorkbookSettings = new GridWorkbookSettings()
 g.Settings=gsettings;
 
'قم بعملك
```

### أنظر أيضا

* مساحة الاسم [Aspose.Cells.GridJs](../../aspose.cells.gridjs)
* المجسم [Aspose.Cells.GridJs](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridJs.dll -->