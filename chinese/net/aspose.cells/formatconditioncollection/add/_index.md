---
title: Add
second_title: Aspose.Cells for .NET API 参考
description: 在 FormatConditions 中添加格式条件和受影响的单元格范围
type: docs
weight: 40
url: /zh/net/aspose.cells/formatconditioncollection/add/
---
## FormatConditionCollection.Add method

在 FormatConditions 中添加格式条件和受影响的单元格范围

```csharp
public int[] Add(CellArea cellArea, FormatConditionType type, OperatorType operatorType, 
    string formula1, string formula2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cellArea | CellArea | 条件格式的单元格范围。 |
| type | FormatConditionType | 条件格式的类型。它可以是 FormatConditionType 的成员之一。 |
| operatorType | OperatorType | 比较运算符。它可以是 OperatorType 的成员之一。 |
| formula1 | String | 与条件格式关联的值或表达式。 |
| formula2 | String | 与条件格式关联的值或表达式 |

### 返回值

[0]：格式化条件对象索引；[1] 影响单元格范围索引。

### 也可以看看

* struct [CellArea](../../cellarea)
* enum [FormatConditionType](../../formatconditiontype)
* enum [OperatorType](../../operatortype)
* class [FormatConditionCollection](../../formatconditioncollection)
* 命名空间 [Aspose.Cells](../../formatconditioncollection)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->