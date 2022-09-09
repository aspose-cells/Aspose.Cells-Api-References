---
title: CustomCommandButtonCollection
second_title: Aspose.Cells for .NET API 参考
description: 代表CustomCommandButton的集合
type: docs
weight: 60
url: /zh/net/aspose.cells.gridweb/customcommandbuttoncollection/
---
## CustomCommandButtonCollection class

代表CustomCommandButton的集合。

```csharp
public class CustomCommandButtonCollection : IList
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.cells.gridweb/customcommandbuttoncollection/count) { get; } | 获取集合的计数。 |
| [IsFixedSize](../../aspose.cells.gridweb/customcommandbuttoncollection/isfixedsize) { get; } | 仅供内部使用。 |
| [IsReadOnly](../../aspose.cells.gridweb/customcommandbuttoncollection/isreadonly) { get; } | 仅供内部使用。 |
| [IsSynchronized](../../aspose.cells.gridweb/customcommandbuttoncollection/issynchronized) { get; } | 仅供内部使用。 |
| [Item](../../aspose.cells.gridweb/customcommandbuttoncollection/item) { get; set; } | 获取索引处的自定义命令按钮对象。 |
| [SyncRoot](../../aspose.cells.gridweb/customcommandbuttoncollection/syncroot) { get; } | 仅供内部使用。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.cells.gridweb/customcommandbuttoncollection/add)(object) | 将自定义命令按钮对象添加到集合中。 |
| [Clear](../../aspose.cells.gridweb/customcommandbuttoncollection/clear)() | 清除集合。 |
| [Contains](../../aspose.cells.gridweb/customcommandbuttoncollection/contains)(object) | 表示自定义命令按钮对象是否在集合中。 |
| [CopyTo](../../aspose.cells.gridweb/customcommandbuttoncollection/copyto)(Array, int) | 将集合复制到数组中。 |
| [GetEnumerator](../../aspose.cells.gridweb/customcommandbuttoncollection/getenumerator)() | 获取集合的 IEnumerator 对象。 |
| [IndexOf](../../aspose.cells.gridweb/customcommandbuttoncollection/indexof)(object) | 获取按钮的索引。 |
| [Insert](../../aspose.cells.gridweb/customcommandbuttoncollection/insert)(int, object) | 在索引处插入一个按钮。 |
| [Remove](../../aspose.cells.gridweb/customcommandbuttoncollection/remove)(object) | 移除自定义命令按钮对象。 |
| [RemoveAt](../../aspose.cells.gridweb/customcommandbuttoncollection/removeat)(int) | 在索引处删除。 |

### 例子

```csharp
[C#]
CustomCommandButton button = new CustomCommandButton();
button.Command = "MyCommand";
button.ImageUrl = "images/button1.gif";
GridWeb1.CustomCommandButtons.Add(button);
[VB]
Dim button As CustomCommandButton =  New CustomCommandButton()
button.Command = "MyCommand"
button.ImageUrl = "images/button1.gif"
GridWeb1.CustomCommandButtons.Add(button)
```

### 也可以看看

* 命名空间 [Aspose.Cells.GridWeb](../../aspose.cells.gridweb)
* 部件 [Aspose.Cells.GridWeb](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->