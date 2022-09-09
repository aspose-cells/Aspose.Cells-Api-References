---
title: AddWordArt
second_title: Aspose.Cells لمرجع .NET API
description: يضيف WordArt معدة مسبقًا منذ Excel 2007.s
type: docs
weight: 350
url: /ar/net/aspose.cells.drawing/shapecollection/addwordart/
---
## ShapeCollection.AddWordArt method

يضيف WordArt معدة مسبقًا منذ Excel 2007.s

```csharp
public Shape AddWordArt(PresetWordArtStyle style, string text, int upperLeftRow, int top, 
    int upperLeftColumn, int left, int height, int width)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| style | PresetWordArtStyle | نمط WordArt المعين مسبقًا. |
| text | String | النص. |
| upperLeftRow | Int32 | فهرس الصف العلوي الأيسر. |
| top | Int32 | يمثل الإزاحة الرأسية للشكل من صفه الأيسر ، بوحدة بكسل. |
| upperLeftColumn | Int32 | فهرس العمود الأيسر العلوي. |
| left | Int32 | يمثل الإزاحة الأفقية للشكل من العمود الأيسر ، بوحدة البكسل. |
| height | Int32 | يمثل ارتفاع الشكل بوحدة البكسل. |
| width | Int32 | يمثل عرض الشكل بوحدة البكسل. |

### أمثلة

```csharp

[C#]
// إضافة WordArt
Shape wordArt2 = shapes.AddWordArt(PresetWordArtStyle.WordArtStyle1, "WordArt", 3, 0, 3, 0, 50, 200);
```

### أنظر أيضا

* class [Shape](../../shape)
* enum [PresetWordArtStyle](../../presetwordartstyle)
* class [ShapeCollection](../../shapecollection)
* مساحة الاسم [Aspose.Cells.Drawing](../../shapecollection)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->