---
title: PdfSecurityOptions
second_title: Aspose.Cells for .NET API Referansı
description: PdfSecurityOptions yapıcısı
type: docs
weight: 10
url: /tr/net/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/pdfsecurityoptions/
---
## PdfSecurityOptions constructor

PdfSecurityOptions yapıcısı

```csharp
public PdfSecurityOptions()
```

### Örnekler

Aşağıdaki kod, çıktı pdf için yüksek çözünürlüklü yazdırma iznini ayarlar.

```csharp
Workbook wb = new Workbook();
wb.Worksheets[0].Cells["A1"].Value = "Aspose";

PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();


PdfSecurityOptions pdfSecurityOptions = new PdfSecurityOptions();

// sahip şifresini ayarla
pdfSecurityOptions.OwnerPassword = "YourOwnerPassword";

//Kullanıcı şifresini ayarla
pdfSecurityOptions.UserPassword = "YourUserPassword";

// yazdırma iznini ayarla
pdfSecurityOptions.PrintPermission = true;

//baskı için yüksek çözünürlüğü ayarla
pdfSecurityOptions.FullQualityPrintPermission = true;


pdfSaveOptions.SecurityOptions = pdfSecurityOptions;

wb.Save("output.pdf", pdfSaveOptions);
```

### Ayrıca bakınız

* class [PdfSecurityOptions](../../pdfsecurityoptions)
* ad alanı [Aspose.Cells.Rendering.PdfSecurity](../../pdfsecurityoptions)
* toplantı [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->