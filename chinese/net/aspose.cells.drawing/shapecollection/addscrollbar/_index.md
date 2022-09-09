---
title: AddScrollBar
second_title: Aspose.Cells for .NET API 参考
description: 将滚动条添加到工作表
type: docs
weight: 250
url: /zh/net/aspose.cells.drawing/shapecollection/addscrollbar/
---
## ShapeCollection.AddScrollBar method

将滚动条添加到工作表。

```csharp
public ScrollBar AddScrollBar(int upperLeftRow, int top, int upperLeftColumn, int left, int height, 
    int width)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| upperLeftRow | Int32 | 左上行索引。 |
| top | Int32 | 表示 ScrollBar 与其左行的垂直偏移量，以像素为单位。 |
| upperLeftColumn | Int32 | 左上列索引。 |
| left | Int32 | 表示 ScrollBar 与其左列的水平偏移量，以像素为单位。 |
| height | Int32 | 表示 ScrollBar 的高度，以像素为单位。 |
| width | Int32 | 表示ScrollBar的宽度，以像素为单位。 |

### 返回值

一个滚动条对象。

### 例子

```csharp

[C#]
//添加滚动条
ScrollBar scrollBar = shapes.AddScrollBar(1, 0, 1, 0, 100, 50);
```

### 也可以看看

* class [ScrollBar](../../scrollbar)
* class [ShapeCollection](../../shapecollection)
* 命名空间 [Aspose.Cells.Drawing](../../shapecollection)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->