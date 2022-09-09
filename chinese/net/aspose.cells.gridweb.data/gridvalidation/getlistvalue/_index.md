---
title: GetListValue
second_title: Aspose.Cells for .NET API 参考
description: 获取指定单元格的验证列表的值
type: docs
weight: 210
url: /zh/net/aspose.cells.gridweb.data/gridvalidation/getlistvalue/
---
## GridValidation.GetListValue method

获取指定单元格的验证列表的值。

```csharp
public object GetListValue(int row, int column)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| row | Int32 | 行索引。 |
| column | Int32 | 列索引。 |

### 返回值

为指定单元格生成此验证列表的值。 如果列表引用范围，则返回值将是一个 ReferredArea 对象； 否则返回值可能是 null、object[] 或简单对象。

### 评论

仅用于类型为 List 且已应用于给定单元格的验证， 否则将返回 null。

### 也可以看看

* class [GridValidation](../../gridvalidation)
* 命名空间 [Aspose.Cells.GridWeb.Data](../../gridvalidation)
* 部件 [Aspose.Cells.GridWeb](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->