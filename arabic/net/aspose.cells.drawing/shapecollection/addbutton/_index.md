---
title: AddButton
second_title: Aspose.Cells لمرجع .NET API
description: يضيف زرًا إلى ورقة العمل .
type: docs
weight: 60
url: /ar/net/aspose.cells.drawing/shapecollection/addbutton/
---
## ShapeCollection.AddButton method

يضيف زرًا إلى ورقة العمل .

```csharp
public Button AddButton(int upperLeftRow, int top, int upperLeftColumn, int left, int height, 
    int width)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| upperLeftRow | Int32 | فهرس الصف العلوي الأيسر. |
| top | Int32 | يمثل الإزاحة الرأسية لـ Button من صفه الأيسر ، بوحدة بكسل. |
| upperLeftColumn | Int32 | فهرس العمود الأيسر العلوي. |
| left | Int32 | يمثل الإزاحة الأفقية لـ Button من عمودها الأيسر ، بوحدة البكسل. |
| height | Int32 | يمثل ارتفاع الزر ، بوحدة البكسل. |
| width | Int32 | يمثل عرض الزر ، بوحدة البكسل. |

### قيمة الإرجاع

كائن زر.

### أمثلة

```csharp

[C#]
// إضافة زر
Button button = shapes.AddButton(1, 0, 1, 0, 100, 50);
```

### أنظر أيضا

* class [Button](../../button)
* class [ShapeCollection](../../shapecollection)
* مساحة الاسم [Aspose.Cells.Drawing](../../shapecollection)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->