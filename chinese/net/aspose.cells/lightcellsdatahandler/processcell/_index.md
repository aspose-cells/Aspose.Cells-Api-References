---
title: ProcessCell
second_title: Aspose.Cells for .NET API 参考
description: 开始处理一个单元格
type: docs
weight: 10
url: /zh/net/aspose.cells/lightcellsdatahandler/processcell/
---
## LightCellsDataHandler.ProcessCell method

开始处理一个单元格。

```csharp
public bool ProcessCell(Cell cell)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cell | Cell | 当前正在处理的单元格对象 |

### 返回值

该单元格是否需要保存在当前工作表的单元格模型中。 一般应该为false，这样所有的单元格在处理后不会保存在内存中，然后保存到内存中。 用于某些特殊用途，例如用户需要访问处理完整个工作簿后的某些单元格， 用户可以使此方法返回 true 以将这些特殊单元格保留在 Cells 模型中，并稍后通过诸如 Cells[row, column] 之类的 API 访问它们。 但是，将单元格数据保留在 Cells 中模型将需要更多内存，如果保留所有单元格，则在 LightCells 模式下读取模板 file 将与以正常方式读取它相同。

### 评论

读取一个单元格的数据后调用。

### 也可以看看

* class [Cell](../../cell)
* interface [LightCellsDataHandler](../../lightcellsdatahandler)
* 命名空间 [Aspose.Cells](../../lightcellsdatahandler)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->