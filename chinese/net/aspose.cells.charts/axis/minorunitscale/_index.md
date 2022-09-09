---
title: MinorUnitScale
second_title: Aspose.Cells for .NET API 参考
description: 表示类别轴的主要单位比例
type: docs
weight: 320
url: /zh/net/aspose.cells.charts/axis/minorunitscale/
---
## Axis.MinorUnitScale property

表示类别轴的主要单位比例。

```csharp
public TimeUnit MinorUnitScale { get; set; }
```

### 例子

```csharp
[C#]

chart.CategoryAxis.CategoryType = CategoryType.TimeScale;
chart.CategoryAxis.MinorUnitScale = TimeUnit.Months;
chart.CategoryAxis.MinorUnit = 2;

[Visual Basic]
chart.CategoryAxis.CategoryType = CategoryType.TimeScale
chart.CategoryAxis.MinorUnitScale = TimeUnit.Months
chart.CategoryAxis.MinorUnit = 2
```

### 也可以看看

* enum [TimeUnit](../../timeunit)
* class [Axis](../../axis)
* 命名空间 [Aspose.Cells.Charts](../../axis)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->