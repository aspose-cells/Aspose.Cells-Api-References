---
title: Characters
second_title: Aspose.Cells for .NET API 参考
description: 返回一个 Characters 对象该对象表示文本中的一系列字符
type: docs
weight: 1000
url: /zh/net/aspose.cells.drawing/shape/characters/
---
## Shape.Characters method

返回一个 Characters 对象，该对象表示文本中的一系列字符。

```csharp
public FontSetting Characters(int startIndex, int length)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | Int32 | 字符开头的索引。 |
| length | Int32 | 字符数。 |

### 返回值

字符对象。

### 评论

此方法仅适用于带有标题的形状。

### 例子

```csharp

[C#]
Aspose.Cells.FontSetting fontSetting = shape.Characters(0, 4);
```

### 也可以看看

* class [FontSetting](../../../aspose.cells/fontsetting)
* class [Shape](../../shape)
* 命名空间 [Aspose.Cells.Drawing](../../shape)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->