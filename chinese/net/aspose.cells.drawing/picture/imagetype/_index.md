---
title: ImageType
second_title: Aspose.Cells for .NET API 参考
description: 获取图片的图像格式
type: docs
weight: 60
url: /zh/net/aspose.cells.drawing/picture/imagetype/
---
## Picture.ImageType property

获取图片的图像格式

```csharp
public ImageType ImageType { get; }
```

### 例子

```csharp

[C#]
//实例化一个工作簿对象
Workbook workbook = new Workbook();
Worksheet worksheet = workbook.Worksheets[0];
//插入第一张图片
int imgIndex1 = worksheet.Pictures.Add(1, 1, "1.png");
//获取插入的图片对象
Picture pic1 = worksheet.Pictures[imgIndex1];
if(pic1.ImageType == Aspose.Cells.Drawing.ImageType.Png)
{
    //图片的类型是png。";
}
//插入第二张图片
int imgIndex2 = worksheet.Pictures.Add(1, 9, "2.jpeg");
//获取插入的图片对象
Picture pic2 = worksheet.Pictures[imgIndex2];
if(pic2.ImageType == Aspose.Cells.Drawing.ImageType.Jpeg)
{
    //图片的类型是jpg。";
}
```

### 也可以看看

* enum [ImageType](../../imagetype)
* class [Picture](../../picture)
* 命名空间 [Aspose.Cells.Drawing](../../picture)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->