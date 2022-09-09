---
title: Walls
second_title: Aspose.Cells for .NET API 参考
description: 封装表示 3-D 图表墙壁的对象
type: docs
weight: 1010
url: /zh/net/aspose.cells.charts/walls/
---
## Walls class

封装表示 3-D 图表墙壁的对象。

```csharp
public class Walls : Floor
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.cells.drawing/area/backgroundcolor) { get; set; } | 获取或设置背景Color的[`Area`](../../aspose.cells.drawing/area). |
| [Border](../../aspose.cells.charts/floor/border) { get; set; } | 获取或设置边框[`Line`](../../aspose.cells.drawing/line). |
| [CenterX](../../aspose.cells.charts/walls/centerx) { get; } | 调用Chart.Calculate()方法后，以图表宽度的1/4000为单位获取墙中心左下角的x坐标。 |
| [CenterXPx](../../aspose.cells.charts/walls/centerxpx) { get; } | 调用Chart.Calculate()方法后，以像素为单位获取墙中心左下角的x坐标。 |
| [CenterY](../../aspose.cells.charts/walls/centery) { get; } | 调用Chart.Calculate()方法后，以图表高度的1/4000为单位获取墙中心左下角的y坐标。 |
| [CenterYPx](../../aspose.cells.charts/walls/centerypx) { get; } | 调用Chart.Calculate()方法后获取墙中心左下角的y坐标，以像素为单位。 |
| [Depth](../../aspose.cells.charts/walls/depth) { get; } | 调用 Chart.Calculate() 方法后，以图表宽度的 1/4000 为单位获取前后深度。 |
| [DepthPx](../../aspose.cells.charts/walls/depthpx) { get; } | 调用 Chart.Calculate() 方法后以像素为单位获取前后深度。 |
| [FillFormat](../../aspose.cells.drawing/area/fillformat) { get; } | 代表一个包含指定图表或形状的填充格式属性的对象。 |
| [ForegroundColor](../../aspose.cells.drawing/area/foregroundcolor) { get; set; } | 获取或设置前景Color. |
| [Formatting](../../aspose.cells.drawing/area/formatting) { get; set; } | 表示区域的格式。 |
| [Height](../../aspose.cells.charts/walls/height) { get; } | 调用 Chart.Calculate() 方法后，以图表高度的 1/4000 为单位获取从上到下的高度。 |
| [HeightPx](../../aspose.cells.charts/walls/heightpx) { get; } | 调用Chart.Calculate() 方法后，以像素为单位获取从上到下的高度。 |
| [InvertIfNegative](../../aspose.cells.drawing/area/invertifnegative) { get; set; } | 如果属性为true，图表点的值为负数， 前景色和背景色会互换 |
| [Transparency](../../aspose.cells.drawing/area/transparency) { get; set; } | 将区域的透明度返回或设置为从 0.0（不透明）到 1.0（透明）的值。 |
| [Width](../../aspose.cells.charts/walls/width) { get; } | 调用 Chart.Calculate() 方法后，以图表宽度的 1/4000 为单位获取从左到右的宽度。 |
| [WidthPx](../../aspose.cells.charts/walls/widthpx) { get; } | 调用Chart.Calculate()方法后获取从左到右的宽度，以像素为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetCubePointCount](../../aspose.cells.charts/walls/getcubepointcount)() | 调用 Chart.Calculate() 方法后获取立方体点数。 |
| [GetCubePointXPx](../../aspose.cells.charts/walls/getcubepointxpx)(int) | 调用Chart.Calculate()方法后获取墙体顶点的x坐标 墙体顶点数为8个 |
| [GetCubePointYPx](../../aspose.cells.charts/walls/getcubepointypx)(int) | 调用Chart.Calculate()方法后获取墙体顶点的y坐标。 墙体顶点数为8个。 |

### 也可以看看

* class [Floor](../floor)
* 命名空间 [Aspose.Cells.Charts](../../aspose.cells.charts)
* 部件 [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->