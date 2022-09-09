---
title: ToImage
second_title: Référence de l'API Aspose.Cells pour .NET
description: Crée limage de la forme et lenregistre dans un flux au format spécifié.
type: docs
weight: 1160
url: /fr/net/aspose.cells.drawing/shape/toimage/
---
## ToImage(Stream, ImageType) {#toimage_1}

Crée l'image de la forme et l'enregistre dans un flux au format spécifié.

```csharp
public void ToImage(Stream stream, ImageType imageType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de sortie. |
| imageType | ImageType | Le type dans lequel enregistrer l'image. |

### Remarques

Les formats suivants sont pris en charge : .bmp, .gif, .jpg, .jpeg, .tiff, .emf.

### Exemples

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
shape.ToImage(imageStream, ImageType.Png);
```

### Voir également

* enum [ImageType](../../imagetype)
* class [Shape](../../shape)
* espace de noms [Aspose.Cells.Drawing](../../shape)
* Assemblée [Aspose.Cells](../../../)

---

## ToImage(string, ImageOrPrintOptions) {#toimage_4}

Enregistre la forme dans un fichier.

```csharp
public void ToImage(string imageFile, ImageOrPrintOptions options)
```

### Exemples

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage("exmaple.png", op);
```

### Voir également

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* espace de noms [Aspose.Cells.Drawing](../../shape)
* Assemblée [Aspose.Cells](../../../)

---

## ToImage(Stream, ImageOrPrintOptions) {#toimage_2}

Enregistre la forme dans un flux.

```csharp
public void ToImage(Stream stream, ImageOrPrintOptions options)
```

### Exemples

```csharp

[C#]
MemoryStream imageStream = new MemoryStream();
ImageOrPrintOptions op = new ImageOrPrintOptions();
shape.ToImage(imageStream, op);
```

### Voir également

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* espace de noms [Aspose.Cells.Drawing](../../shape)
* Assemblée [Aspose.Cells](../../../)

---

## ToImage(ImageOrPrintOptions) {#toimage}

Renvoie l'objet bitmap de la forme .

```csharp
public Bitmap ToImage(ImageOrPrintOptions options)
```

### Exemples

```csharp

[C#]
ImageOrPrintOptions op = new ImageOrPrintOptions();
System.Drawing.Bitmap btm = shape.ToImage(op);
```

### Voir également

* class [ImageOrPrintOptions](../../../aspose.cells.rendering/imageorprintoptions)
* class [Shape](../../shape)
* espace de noms [Aspose.Cells.Drawing](../../shape)
* Assemblée [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->