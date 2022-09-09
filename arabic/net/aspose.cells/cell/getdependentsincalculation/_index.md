---
title: GetDependentsInCalculation
second_title: Aspose.Cells لمرجع .NET API
description: يحصل على كافة الخلايا التي تعتمد نتيجتها المحسوبة على هذه الخلية.
type: docs
weight: 390
url: /ar/net/aspose.cells/cell/getdependentsincalculation/
---
## Cell.GetDependentsInCalculation method

يحصل على كافة الخلايا التي تعتمد نتيجتها المحسوبة على هذه الخلية.

```csharp
public IEnumerator GetDependentsInCalculation(bool recursive)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| recursive | Boolean | ما إذا كان يُرجع هؤلاء المعالين الذين لا يشيرون إلى هذه الخلية مباشرة ولكن بالإشارة إلى الأوراق الأخرى لهذه الخلية |

### قيمة الإرجاع

العداد لتعداد جميع المعالين (كائنات الخلية)

### ملاحظات

لاستخدام هذه الطريقة ، يرجى التأكد من تعيين المصنف بقيمة حقيقية لـ [`EnableCalculationChain`](../../formulasettings/enablecalculationchain) وتم حسابه بالكامل باستخدام هذا الإعداد. إذا لم يكن هناك مرجع صيغة لهذه الخلية ، فسيتم إرجاع قيمة فارغة.

### أمثلة

```csharp
[C#]

Workbook workbook = new Workbook();
Cells cells = workbook.Worksheets[0].Cells;
cells["A1"].Formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2";
cells["A2"].Formula = "=IF(TRUE,B2,B1)";
workbook.Settings.FormulaSettings.EnableCalculationChain = true;
workbook.CalculateFormula();
IEnumerator en = cells["B1"].GetDependentsInCalculation(false);
Console.WriteLine("B1's calculation dependents:");
while(en.MoveNext())
{
    Cell c = (Cell)en.Current;
    Console.WriteLine(c.Name);
}
en = cells["B2"].GetDependentsInCalculation(false);
Console.WriteLine("B2's calculation dependents:");
while(en.MoveNext())
{
    Cell c = (Cell)en.Current;
    Console.WriteLine(c.Name);
}
```

### أنظر أيضا

* class [Cell](../../cell)
* مساحة الاسم [Aspose.Cells](../../cell)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->