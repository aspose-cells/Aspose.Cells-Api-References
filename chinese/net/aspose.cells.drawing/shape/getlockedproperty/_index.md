---
title: GetLockedProperty
second_title: Aspose.Cells for .NET API 参考
description: 获取锁定属性的值
type: docs
weight: 1060
url: /zh/net/aspose.cells.drawing/shape/getlockedproperty/
---
## Shape.GetLockedProperty method

获取锁定属性的值。

```csharp
public bool GetLockedProperty(ShapeLockType type)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| type | ShapeLockType | 形状锁定属性的类型。 |

### 返回值

返回锁定属性的值。

### 例子

```csharp

[C#]
int noAdjustHandles = 0;
if (shape.GetLockedProperty(ShapeLockType.AdjustHandles))
    noAdjustHandles = 1;
```

### 也可以看看

* enum [ShapeLockType](../../shapelocktype)
* class [Shape](../../shape)
* 命名空间 [Aspose.Cells.Drawing](../../shape)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->