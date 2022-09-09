---
title: ToImage
second_title: Aspose.Cells for .NET API 参考
description: 创建形状图像并将其保存到指定格式的流中
type: docs
weight: 1160
url: /zh/net/aspose.cells.drawing/shape/toimage/
---
## ToImage(Stream, ImageType) {#toimage_1}

创建形状图像并将其保存到指定格式的流中。

```csharp
public void ToImage(Stream stream, ImageType imageType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| imageType | ImageType | 保存图像的类型。 |

### 评论

支持以下格式： .bmp、.gif、.jpg、.jpeg、.tiff、.emf。

### 例子

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
shape.ToImage(imageStream, ImageType.Png);
```

### 也可以看看

* enum [ImageType](../../imagetype)
* class [Shape](../../shape)
* 命名空间 [Aspose.Cells.Drawing](../../shape)
* 部件 [Aspose.Cells](../../../)

---

## ToImage(string, ImageOrPrintOptions) {#toimage_4}

将形状保存到文件中。

```csharp
public void ToImage(string imageFile, ImageOrPrintOptions options)
```

### 例子

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage("exmaple.png", op);
```

### 也可以看看

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* 命名空间 [Aspose.Cells.Drawing](../../shape)
* 部件 [Aspose.Cells](../../../)

---

## ToImage(Stream, ImageOrPrintOptions) {#toimage_2}

将形状保存到流中。

```csharp
public void ToImage(Stream stream, ImageOrPrintOptions options)
```

### 例子

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage(imageStream, op);
```

### 也可以看看

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* 命名空间 [Aspose.Cells.Drawing](../../shape)
* 部件 [Aspose.Cells](../../../)

---

## ToImage(ImageOrPrintOptions) {#toimage}

返回形状 . 的位图对象

```csharp
public Bitmap ToImage(ImageOrPrintOptions options)
```

### 例子

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
System.Drawing.Bitmap btm = shape.ToImage(op);
```

### 也可以看看

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* 命名空间 [Aspose.Cells.Drawing](../../shape)
* 部件 [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->