---
title: ToImage
second_title: Справочник по Aspose.Cells для .NET API
description: Создает изображение фигуры и сохраняет его в потоке в указанном формате.
type: docs
weight: 1160
url: /ru/net/aspose.cells.drawing/shape/toimage/
---
## ToImage(Stream, ImageType) {#toimage_1}

Создает изображение фигуры и сохраняет его в потоке в указанном формате.

```csharp
public void ToImage(Stream stream, ImageType imageType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| imageType | ImageType | Тип, в котором нужно сохранить изображение. |

### Примечания

Поддерживаются следующие форматы: .bmp, .gif, .jpg, .jpeg, .tiff, .emf.

### Примеры

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
shape.ToImage(imageStream, ImageType.Png);
```

### Смотрите также

* enum [ImageType](../../imagetype)
* class [Shape](../../shape)
* пространство имен [Aspose.Cells.Drawing](../../shape)
* сборка [Aspose.Cells](../../../)

---

## ToImage(string, ImageOrPrintOptions) {#toimage_4}

Сохраняет фигуру в файл.

```csharp
public void ToImage(string imageFile, ImageOrPrintOptions options)
```

### Примеры

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage("exmaple.png", op);
```

### Смотрите также

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* пространство имен [Aspose.Cells.Drawing](../../shape)
* сборка [Aspose.Cells](../../../)

---

## ToImage(Stream, ImageOrPrintOptions) {#toimage_2}

Сохраняет форму в поток.

```csharp
public void ToImage(Stream stream, ImageOrPrintOptions options)
```

### Примеры

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage(imageStream, op);
```

### Смотрите также

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* пространство имен [Aspose.Cells.Drawing](../../shape)
* сборка [Aspose.Cells](../../../)

---

## ToImage(ImageOrPrintOptions) {#toimage}

Возвращает растровый объект формы .

```csharp
public Bitmap ToImage(ImageOrPrintOptions options)
```

### Примеры

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
System.Drawing.Bitmap btm = shape.ToImage(op);
```

### Смотрите также

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* пространство имен [Aspose.Cells.Drawing](../../shape)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->