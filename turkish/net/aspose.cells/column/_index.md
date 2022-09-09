---
title: Column
second_title: Aspose.Cells for .NET API Referansı
description: Bir çalışma sayfasındaki tek bir sütunu temsil eder.
type: docs
weight: 1060
url: /tr/net/aspose.cells/column/
---
## Column class

Bir çalışma sayfasındaki tek bir sütunu temsil eder.

```csharp
public class Column
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GroupLevel](../../aspose.cells/column/grouplevel) { get; } | Sütunun grup düzeyini alır. |
| [Index](../../aspose.cells/column/index) { get; } | Bu sütunun dizinini alır. |
| [IsCollapsed](../../aspose.cells/column/iscollapsed) { get; set; } | sütunun daraltılmış olup olmadığı |
| [IsHidden](../../aspose.cells/column/ishidden) { get; set; } | Sütunun gizli olup olmadığını gösterir. |
| [Style](../../aspose.cells/column/style) { get; } | Bu sütunun stilini alır. |
| [Width](../../aspose.cells/column/width) { get; set; } | Sütun genişliğini karakter birimi cinsinden alır ve ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ApplyStyle](../../aspose.cells/column/applystyle)(Style, StyleFlag) | Tüm sütun için biçimleri uygular. |

### Örnekler

```csharp

[C#]

//Bir Çalışma Kitabı nesnesini başlatma
Workbook workbook = new Workbook();

//İlk çalışma sayfasının referansının alınması
Worksheet worksheet = workbook.Worksheets[0];
Style style = workbook.CreateStyle();

//Arka plan rengini Mavi olarak ayarlama
style.BackgroundColor = Color.Blue;

//Ön plan rengini Kırmızı olarak ayarlama
style.ForegroundColor= Color.Red;

// Arka Plan Desenini ayarlama
style.Pattern = BackgroundType.DiagonalStripe;

//Yeni Stil Bayrağı
StyleFlag styleFlag = new StyleFlag();

// Tüm Stilleri Ayarla
styleFlag.All = true;

//İlk Sütunu al
Column column = worksheet.Cells.Columns[0];

// Stili ilk sütuna uygula
column.ApplyStyle(style, styleFlag);

//Excel dosyasını kaydetme
workbook.Save("book1.xls");

[VB.NET]

'Bir Çalışma Kitabı nesnesini başlatma
Dim workbook As Workbook = New Workbook()

'İlk çalışma sayfasının referansının alınması
Dim worksheet As Worksheet = workbook.Worksheets(0)

Dim style As Style = workbook.CreateStyle()

'Arka plan rengini Mavi olarak ayarlama
style.BackgroundColor = Color.Blue

'Ön plan rengini Kırmızı olarak ayarlama
style.ForegroundColor = Color.Red

'Arka Plan Desenini ayarlama
style.Pattern = BackgroundType.DiagonalStripe

'Yeni Stil Bayrağı
Dim styleFlag As New StyleFlag()

'Tüm Stilleri Ayarla
styleFlag.All = True

'İlk Sütunu Alın
Dim column As Column = worksheet.Cells.Columns(0)

'Stili İlk Sütuna Uygula
column.ApplyStyle(style, styleFlag)

'Excel dosyasını kaydetme
workbook.Save("book1.xls")
```

### Ayrıca bakınız

* ad alanı [Aspose.Cells](../../aspose.cells)
* toplantı [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->