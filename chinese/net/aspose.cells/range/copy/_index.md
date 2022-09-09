---
title: Copy
second_title: Aspose.Cells for .NET API 参考
description: 使用粘贴特殊选项复制范围
type: docs
weight: 230
url: /zh/net/aspose.cells/range/copy/
---
## Copy(Range, PasteOptions) {#copy_1}

使用粘贴特殊选项复制范围。

```csharp
public void Copy(Range range, PasteOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| range | Range | 源范围。 |
| options | PasteOptions | 粘贴特殊选项。 |

### 也可以看看

* class [PasteOptions](../../pasteoptions)
* class [Range](../../range)
* 命名空间 [Aspose.Cells](../../range)
* 部件 [Aspose.Cells](../../../)

---

## Copy(Range) {#copy}

从源范围复制数据（包括公式）、格式、绘图对象等。

```csharp
public void Copy(Range range)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| range | Range | 资源[`Range`](../../range)目的。 |

### 例子

```csharp

[C#]

//实例化一个工作簿对象
Workbook workbook = new Workbook();
// 获取第一个工作表单元格。
Cells cells = workbook.Worksheets[0].Cells;
Range range1 = cells.CreateRange("A1:A5");
Range range2 = cells.CreateRange("A6:A10");
//复制范围。
range1.Copy(range2);
//保存Excel文件
workbook.Save("book1.xlsm");

 [Visual Basic]

'实例化工作簿对象
Dim workbook As Workbook = New Workbook()
'获取第一个工作表单元格。
Dim cells as Cells = workbook.Worksheets[0].Cells
Range range1 = cells.CreateRange("A1:A5")
Range range2 = cells.CreateRange("A6:A10")
//复制范围
range1.Copy(range2)
'保存 Excel 文件
workbook.Save("book1.xlsm")
```

### 也可以看看

* class [Range](../../range)
* 命名空间 [Aspose.Cells](../../range)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->