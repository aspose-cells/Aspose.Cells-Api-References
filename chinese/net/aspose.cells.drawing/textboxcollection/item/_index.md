---
title: Item
second_title: Aspose.Cells for .NET API 参考
description: 获取TextBoxaspose.cells.drawing/textbox指定索引处的元素
type: docs
weight: 10
url: /zh/net/aspose.cells.drawing/textboxcollection/item/
---
## TextBoxCollection indexer (1 of 2)

获取[`TextBox`](../../textbox)指定索引处的元素。

```csharp
public TextBox this[int index] { get; }
```

| 范围 | 描述 |
| --- | --- |
| index | 元素的从零开始的索引。 |

### 返回值

指定索引处的元素。

### 例子

```csharp

[C#]
int index = textBoxCollection.Count - 1;
TextBox txb = textBoxCollection[index];
```

### 也可以看看

* class [TextBox](../../textbox)
* class [TextBoxCollection](../../textboxcollection)
* 命名空间 [Aspose.Cells.Drawing](../../textboxcollection)
* 部件 [Aspose.Cells](../../../)

---

## TextBoxCollection indexer (2 of 2)

获取[`TextBox`](../../textbox)元素名称.

```csharp
public TextBox this[string name] { get; }
```

| 范围 | 描述 |
| --- | --- |
| name | 文本框的名称。 |

### 例子

```csharp

[C#]
string txtboxName = "textbox 1"; 
TextBox txb2 = textBoxCollection[txtboxName];
if(txb2 != null)
{
    //做你想做的
}
```

### 也可以看看

* class [TextBox](../../textbox)
* class [TextBoxCollection](../../textboxcollection)
* 命名空间 [Aspose.Cells.Drawing](../../textboxcollection)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->