---
title: LineFormat
second_title: Aspose.Cells for .NET API 参考
description: 代表线路的所有设置
type: docs
weight: 2220
url: /zh/net/aspose.cells.drawing/lineformat/
---
## LineFormat class

代表线路的所有设置。

```csharp
public class LineFormat : FillFormat
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BeginArrowheadLength](../../aspose.cells.drawing/lineformat/beginarrowheadlength) { get; set; } | 获取和设置行的开始箭头长度类型。 |
| [BeginArrowheadStyle](../../aspose.cells.drawing/lineformat/beginarrowheadstyle) { get; set; } | 获取和设置行的开始箭头类型。 |
| [BeginArrowheadWidth](../../aspose.cells.drawing/lineformat/beginarrowheadwidth) { get; set; } | 获取和设置线条的开始箭头宽度类型。 |
| [CapType](../../aspose.cells.drawing/lineformat/captype) { get; set; } | 指定结尾大写。 |
| [CompoundType](../../aspose.cells.drawing/lineformat/compoundtype) { get; set; } | 指定线复合类型。 |
| [DashStyle](../../aspose.cells.drawing/lineformat/dashstyle) { get; set; } | 指定虚线类型。 |
| [EndArrowheadLength](../../aspose.cells.drawing/lineformat/endarrowheadlength) { get; set; } | 获取和设置线条的结束箭头长度类型。 |
| [EndArrowheadStyle](../../aspose.cells.drawing/lineformat/endarrowheadstyle) { get; set; } | 获取和设置行的结束箭头类型。 |
| [EndArrowheadWidth](../../aspose.cells.drawing/lineformat/endarrowheadwidth) { get; set; } | 获取和设置线条的结束箭头宽度类型。 |
| [FillType](../../aspose.cells.drawing/fillformat/filltype) { get; set; } | 获取和设置填充类型 |
| [GradientColor1](../../aspose.cells.drawing/fillformat/gradientcolor1) { get; } | 返回指定填充的渐变颜色 1。 |
| [GradientColor2](../../aspose.cells.drawing/fillformat/gradientcolor2) { get; } | 返回指定填充的渐变颜色 2。 |
| [GradientColorType](../../aspose.cells.drawing/fillformat/gradientcolortype) { get; } | 返回指定填充的渐变颜色类型。 |
| [GradientDegree](../../aspose.cells.drawing/fillformat/gradientdegree) { get; } | 返回指定填充的渐变度。 仅适用于 Excel 2007。 |
| [GradientFill](../../aspose.cells.drawing/fillformat/gradientfill) { get; } | 获取[`GradientFill`](../fillformat/gradientfill)对象. |
| [GradientStyle](../../aspose.cells.drawing/fillformat/gradientstyle) { get; } | 返回指定填充的渐变样式。 |
| [GradientVariant](../../aspose.cells.drawing/fillformat/gradientvariant) { get; } | 返回指定填充的渐变变量。 仅适用于 Excel 2007。 |
| [ImageData](../../aspose.cells.drawing/fillformat/imagedata) { get; set; } | 获取和设置图片图像数据。 |
| [JoinType](../../aspose.cells.drawing/lineformat/jointype) { get; set; } | 指定线连接类型。 |
| [Pattern](../../aspose.cells.drawing/fillformat/pattern) { get; set; } | 代表一个区域的显示模式。 |
| [PatternFill](../../aspose.cells.drawing/fillformat/patternfill) { get; } | 获取[`PatternFill`](../fillformat/patternfill)对象. |
| [PictureFormatType](../../aspose.cells.drawing/fillformat/pictureformattype) { get; set; } | 获取和设置图片格式类型。 |
| [PresetColor](../../aspose.cells.drawing/fillformat/presetcolor) { get; } | 返回指定填充的渐变预设颜色。 |
| [Scale](../../aspose.cells.drawing/fillformat/scale) { get; set; } | 获取和设置图片格式比例。 |
| [SolidFill](../../aspose.cells.drawing/fillformat/solidfill) { get; } | 获取[`SolidFill`](../fillformat/solidfill)对象. |
| [Texture](../../aspose.cells.drawing/fillformat/texture) { get; set; } | 表示指定填充的纹理类型。 |
| [TextureFill](../../aspose.cells.drawing/fillformat/texturefill) { get; } | 获取[`TextureFill`](../fillformat/texturefill)对象. |
| [Transparency](../../aspose.cells.drawing/fillformat/transparency) { get; set; } | 将区域的透明度返回或设置为从 0.0（不透明）到 1.0（透明）的值。 |
| [Weight](../../aspose.cells.drawing/lineformat/weight) { get; set; } | 获取或设置线的权重，以点为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.cells.drawing/lineformat/equals)(object) | 确定此实例是否与另一个指定的值相同[`LineFormat`](../lineformat)对象. |
| override [GetHashCode](../../aspose.cells.drawing/lineformat/gethashcode)() | 获取哈希码。 |
| [SetOneColorGradient](../../aspose.cells.drawing/fillformat/setonecolorgradient)(Color, double, GradientStyleType, int) | 将指定的填充设置为单色渐变。 仅适用于 Excel 2007。 |
| [SetPresetColorGradient](../../aspose.cells.drawing/fillformat/setpresetcolorgradient)(GradientPresetType, GradientStyleType, int) | 将指定的填充设置为预设颜色渐变。 仅适用于 Excel 2007。 |
| [SetTwoColorGradient](../../aspose.cells.drawing/fillformat/settwocolorgradient)(Color, Color, GradientStyleType, int) | 将指定的填充设置为双色渐变。 仅适用于 Excel 2007。 |
| [SetTwoColorGradient](../../aspose.cells.drawing/fillformat/settwocolorgradient)(Color, double, Color, double, GradientStyleType, int) | 将指定的填充设置为双色渐变。 仅适用于 Excel 2007。 |

### 例子

```csharp

[C#]
//实例化一个工作簿对象
Workbook workbook = new Workbook();
ShapeCollection shapes = workbook.Worksheets[0].Shapes;
Shape shape = shapes.AddRectangle(1, 0, 1, 0, 50, 100);
LineFormat lineFmt = shape.Line;

//做你的事

```

### 也可以看看

* class [FillFormat](../fillformat)
* 命名空间 [Aspose.Cells.Drawing](../../aspose.cells.drawing)
* 部件 [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->