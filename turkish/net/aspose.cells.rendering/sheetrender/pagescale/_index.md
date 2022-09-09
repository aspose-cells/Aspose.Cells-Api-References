---
title: PageScale
second_title: Aspose.Cells for .NET API Referansı
description: Sayfanın hesaplanan sayfa ölçeğini alır. Zoomaspose.cells/pagesetup/zoom ayarlanır. Aksi takdirde hesaplanan ölçeği şuna göre döndürürFitToPagesWideaspose.cells/pagesetup/fittopageswide veFitToPagesTallaspose.cells/pagesetup/fittopagestall .
type: docs
weight: 30
url: /tr/net/aspose.cells.rendering/sheetrender/pagescale/
---
## SheetRender.PageScale property

Sayfanın hesaplanan sayfa ölçeğini alır. [`Zoom`](../../../aspose.cells/pagesetup/zoom) ayarlanır. Aksi takdirde, hesaplanan ölçeği şuna göre döndürür:[`FitToPagesWide`](../../../aspose.cells/pagesetup/fittopageswide) ve[`FitToPagesTall`](../../../aspose.cells/pagesetup/fittopagestall) .

```csharp
public double PageScale { get; }
```

### Örnekler

```csharp
Workbook wb = new Workbook("Book1.xlsx");

SheetRender sheetRender = new SheetRender(wb.Worksheets[0], new ImageOrPrintOptions());

// Sayfanın hesaplanan sayfa ölçeğini alır.
double pageScale = sheetRender.PageScale;
```

### Ayrıca bakınız

* class [SheetRender](../../sheetrender)
* ad alanı [Aspose.Cells.Rendering](../../sheetrender)
* toplantı [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->