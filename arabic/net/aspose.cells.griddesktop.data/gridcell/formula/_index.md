---
title: Formula
second_title: Aspose.Cells لمرجع .NET API
description: الحصول على صيغة ملفCell .
type: docs
weight: 70
url: /ar/net/aspose.cells.griddesktop.data/gridcell/formula/
---
## GridCell.Formula property

الحصول على صيغة ملفCell .

```csharp
public string Formula { get; set; }
```

### ملاحظات

تبدأ سلسلة الصيغة دائمًا بعلامة التساوي (=) . ويرجى دائمًا استخدام الفاصلة (،) كمحدد للمعلمات ، مثل "= SUM (A1، E1، H2)".

يمكن للمستخدم تعيين أي صيغة في ملف مصمم المصنف. ستحتفظ Aspose.Cells بجميع الصيغ. إذا استخدم المستخدم هذه الخاصية لتعيين صيغة إلى خلية ، يتم دعم جزء كبير من الدوال المضمنة في المصنف. والمزيد قادم. إذا كان لديك أي حاجة خاصة للوظائف المضمنة في المصنف ، يرجى إعلامنا.

### أمثلة

```csharp
[C#]
	cell.Formula = "=SUM(A1:C3) + E6*2";
[Visual Basic]
	cell.Formula = "=SUM(A1:C3) + E6*2"
```

### أنظر أيضا

* class [GridCell](../../gridcell)
* مساحة الاسم [Aspose.Cells.GridDesktop.Data](../../gridcell)
* المجسم [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->