---
title: SetImageResample
second_title: Aspose.Cells für .NET-API-Referenz
description: Legt die gewünschte PPI Pixel pro Zoll von Resample-Bildern und JPEG-Qualität fest. Alle Bilder werden mit der angegebenen Qualitätseinstellung in JPEG konvertiert und Bilder die größer als die angegebene PPI Pixel pro Zoll sind werden neu berechnet.
type: docs
weight: 320
url: /de/net/aspose.cells/pdfsaveoptions/setimageresample/
---
## PdfSaveOptions.SetImageResample method

Legt die gewünschte PPI (Pixel pro Zoll) von Resample-Bildern und JPEG-Qualität fest. Alle Bilder werden mit der angegebenen Qualitätseinstellung in JPEG konvertiert, und Bilder, die größer als die angegebene PPI (Pixel pro Zoll) sind, werden neu berechnet.

```csharp
public void SetImageResample(int desiredPPI, int jpegQuality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| desiredPPI | Int32 | Gewünschte Pixel pro Zoll. 220 hohe Qualität. 150 Bildschirmqualität. 96 E-Mail-Qualität. |
| jpegQuality | Int32 | 0 - 100 % JPEG-Qualität. |

### Beispiele

Der folgende Code setzt die gewünschte PPI auf 96 und die JPEG-Qualität auf 80 für Bilder in der Ausgabe pdf.

```csharp
//Lade die Quelldatei mit Bildern.
Workbook wb = new Workbook("Book1.xlsx");

PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

// Stellen Sie die gewünschte PPI auf 96 und die JPEG-Qualität auf 80 ein.
pdfSaveOptions.SetImageResample(96, 80);

wb.Save("output.pdf", pdfSaveOptions);
```

### Siehe auch

* class [PdfSaveOptions](../../pdfsaveoptions)
* namensraum [Aspose.Cells](../../pdfsaveoptions)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->