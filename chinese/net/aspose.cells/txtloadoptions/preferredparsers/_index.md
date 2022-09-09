---
title: PreferredParsers
second_title: Aspose.Cells for .NET API 参考
description: 获取和设置用于加载文本文件的首选值解析器
type: docs
weight: 60
url: /zh/net/aspose.cells/txtloadoptions/preferredparsers/
---
## TxtLoadOptions.PreferredParsers property

获取和设置用于加载文本文件的首选值解析器。

```csharp
public ICustomParser[] PreferredParsers { get; set; }
```

### 评论

parsers[0] 是解析器将用于文本模板文件中的第一列， parsers[1] 是将解析器用于第二列，...等等。 最后一个（parsers[parsers. length-1]) 将用于所有其他从parsers.length-1. 开始的列

### 也可以看看

* interface [ICustomParser](../../icustomparser)
* class [TxtLoadOptions](../../txtloadoptions)
* 命名空间 [Aspose.Cells](../../txtloadoptions)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->