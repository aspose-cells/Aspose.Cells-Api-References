---
title: ToImage
second_title: Aspose.Cells för .NET API-referens
description: Skapar formbilden och sparar den i en ström i angivet format.
type: docs
weight: 1160
url: /sv/net/aspose.cells.drawing/shape/toimage/
---
## ToImage(Stream, ImageType) {#toimage_1}

Skapar formbilden och sparar den i en ström i angivet format.

```csharp
public void ToImage(Stream stream, ImageType imageType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Utgångsströmmen. |
| imageType | ImageType | Typen där bilden ska sparas. |

### Anmärkningar

Följande format stöds: .bmp, .gif, .jpg, .jpeg, .tiff, .emf.

### Exempel

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
shape.ToImage(imageStream, ImageType.Png);
```

### Se även

* enum [ImageType](../../imagetype)
* class [Shape](../../shape)
* namnutrymme [Aspose.Cells.Drawing](../../shape)
* hopsättning [Aspose.Cells](../../../)

---

## ToImage(string, ImageOrPrintOptions) {#toimage_4}

Sparar formen till en fil.

```csharp
public void ToImage(string imageFile, ImageOrPrintOptions options)
```

### Exempel

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage("exmaple.png", op);
```

### Se även

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* namnutrymme [Aspose.Cells.Drawing](../../shape)
* hopsättning [Aspose.Cells](../../../)

---

## ToImage(Stream, ImageOrPrintOptions) {#toimage_2}

Sparar formen i en ström.

```csharp
public void ToImage(Stream stream, ImageOrPrintOptions options)
```

### Exempel

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage(imageStream, op);
```

### Se även

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* namnutrymme [Aspose.Cells.Drawing](../../shape)
* hopsättning [Aspose.Cells](../../../)

---

## ToImage(ImageOrPrintOptions) {#toimage}

Returnerar bitmappsobjektet för formen .

```csharp
public Bitmap ToImage(ImageOrPrintOptions options)
```

### Exempel

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
System.Drawing.Bitmap btm = shape.ToImage(op);
```

### Se även

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* namnutrymme [Aspose.Cells.Drawing](../../shape)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->