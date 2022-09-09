---
title: AddTextEffect
second_title: Aspose.Cells for .NET API 参考
description: 插入艺术字对象
type: docs
weight: 330
url: /zh/net/aspose.cells.drawing/shapecollection/addtexteffect/
---
## ShapeCollection.AddTextEffect method

插入艺术字对象。

```csharp
public Shape AddTextEffect(MsoPresetTextEffect effect, string text, string fontName, int size, 
    bool fontBold, bool fontItalic, int upperLeftRow, int top, int upperLeftColumn, int left, 
    int height, int width)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| effect | MsoPresetTextEffect | mso 预设文字效果类型。 |
| text | String | 艺术字文本。 |
| fontName | String | 字体名称。 |
| size | Int32 | 字体大小 |
| fontBold | Boolean | 指示字体是否为粗体。 |
| fontItalic | Boolean | 指示字体是否为斜体。 |
| upperLeftRow | Int32 | 左上行索引。 |
| top | Int32 | 表示形状与其左行的垂直偏移量，以像素为单位。 |
| upperLeftColumn | Int32 | 左上列索引。 |
| left | Int32 | 表示形状与其左列的水平偏移量，以像素为单位。 |
| height | Int32 | 表示形状的高度，以像素为单位。 |
| width | Int32 | 表示形状的宽度，以像素为单位。 |

### 返回值

返回一个表示新艺术字对象的 Shape 对象。

### 例子

```csharp

[C#]
//添加一个艺术字
Shape wordArt1 = shapes.AddTextEffect(MsoPresetTextEffect.TextEffect10, "WordArt", "arial", 18, false, false, 3, 0, 3, 0, 200, 50);
```

### 也可以看看

* class [Shape](../../shape)
* enum [MsoPresetTextEffect](../../msopresettexteffect)
* class [ShapeCollection](../../shapecollection)
* 命名空间 [Aspose.Cells.Drawing](../../shapecollection)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->