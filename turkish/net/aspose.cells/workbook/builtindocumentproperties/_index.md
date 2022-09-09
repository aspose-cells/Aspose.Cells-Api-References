---
title: BuiltInDocumentProperties
second_title: Aspose.Cells for .NET API Referansı
description: Bir döndürürDocumentPropertyaspose.cells.properties/documentpropertyelektronik tablonun tüm yerleşik belge özelliklerini temsil eden koleksiyon.
type: docs
weight: 30
url: /tr/net/aspose.cells/workbook/builtindocumentproperties/
---
## Workbook.BuiltInDocumentProperties property

Bir döndürür[`DocumentProperty`](../../../aspose.cells.properties/documentproperty)elektronik tablonun tüm yerleşik belge özelliklerini temsil eden koleksiyon.

```csharp
public BuiltInDocumentPropertyCollection BuiltInDocumentProperties { get; }
```

### Notlar

Yerleşik belge özellikleri listesine yeni bir özellik eklenemez. Yalnızca yerleşik bir özelliği alabilir ve değerini değiştirebilirsiniz. Yerleşik özellikler adı listesi aşağıdadır:

Başlık

Ders

Yazar

anahtar kelimeler

Yorumlar

Şablon

Son Yazar

Revizyon numarası

Uygulama Adı

Son Baskı Tarihi

Oluşturulma tarihi

Son Tasarruf Süresi

Toplam Düzenleme Süresi

Sayfa sayısı

Kelime Sayısı

Karakter sayısı

Güvenlik

Kategori

Biçim

Müdür

Şirket

Bayt Sayısı

Hat Sayısı

Paragraf Sayısı

Slayt Sayısı

Not Sayısı

Gizli Slayt Sayısı

Multimedya Klip Sayısı

### Örnekler

```csharp
[C#]
Workbook workbook = new Workbook();
DocumentProperty doc = workbook.BuiltInDocumentProperties["Author"];
doc.Value = "John Smith";

[Visual Basic]
Dim workbook as Workbook = New Workbook()
Dim doc as DocumentProperty = workbook.BuiltInDocumentProperties("Author")
doc.Value = "John Smith"
```

### Ayrıca bakınız

* class [BuiltInDocumentPropertyCollection](../../../aspose.cells.properties/builtindocumentpropertycollection)
* class [Workbook](../../workbook)
* ad alanı [Aspose.Cells](../../workbook)
* toplantı [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->