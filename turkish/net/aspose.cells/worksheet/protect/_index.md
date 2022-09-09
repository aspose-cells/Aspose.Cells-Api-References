---
title: Protect
second_title: Aspose.Cells for .NET API Referansı
description: Çalışma sayfasını korur.
type: docs
weight: 770
url: /tr/net/aspose.cells/worksheet/protect/
---
## Protect(ProtectionType) {#protect}

Çalışma sayfasını korur.

```csharp
public void Protect(ProtectionType type)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | ProtectionType | Koruma türü. |

### Notlar

Bu yöntem, çalışma sayfasını parola olmadan korur. Excel dosyasının tüm sürümlerinde çalışma sayfasını koruyabilir.

### Ayrıca bakınız

* enum [ProtectionType](../../protectiontype)
* class [Worksheet](../../worksheet)
* ad alanı [Aspose.Cells](../../worksheet)
* toplantı [Aspose.Cells](../../../)

---

## Protect(ProtectionType, string, string) {#protect_1}

Çalışma sayfasını korur.

```csharp
public void Protect(ProtectionType type, string password, string oldPassword)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| type | ProtectionType | Koruma türü. |
| password | String | Şifre. |
| oldPassword | String | Çalışma sayfası zaten bir parola ile korunuyorsa, lütfen eski parolayı girin. Aksi takdirde, bu parametreye boş bir değer veya boş bir dize ayarlayabilirsiniz. |

### Notlar

Bu yöntem, Excel dosyasının tüm sürümlerinde çalışma sayfasını koruyabilir.

### Örnekler

```csharp

[C#]

//Bir Çalışma Kitabı nesnesini başlatma
Workbook excel = new Workbook("template.xlsx");
//Excel dosyasındaki ilk çalışma sayfasına erişim
Worksheet worksheet = excel.Worksheets[0];
//Çalışma sayfasını bir parola ile koruma
worksheet.Protect(ProtectionType.All, "aspose", null);
//Değiştirilen Excel dosyasını varsayılan (yani Excel 20003) biçiminde kaydetme
excel.Save("output.xls");
//Tüm kaynakları boşaltmak için dosya akışını kapatıyoruz

[Visual Basic]

'Açılacak Excel dosyasını içeren bir dosya akışı oluşturma
Dim fstream As FileStream = New FileStream("book1.xls", FileMode.Open)
'Bir Çalışma Kitabı nesnesinin örneğini oluşturma ve Excel dosyasını dosya akışı yoluyla açma
Dim excel As Workbook = New Workbook(fstream)
'Excel dosyasındaki ilk çalışma sayfasına erişme
Dim worksheet As Worksheet = excel.Worksheets(0)
'Çalışma sayfasını bir parola ile koruma
worksheet.Protect(ProtectionType.All, "aspose", DBNull.Value.ToString())
'Değiştirilen Excel dosyasını varsayılan (yani Excel 20003) biçiminde kaydetme
excel.Save("output.xls")
'Tüm kaynakları boşaltmak için dosya akışını kapatma
fstream.Close()

```

### Ayrıca bakınız

* enum [ProtectionType](../../protectiontype)
* class [Worksheet](../../worksheet)
* ad alanı [Aspose.Cells](../../worksheet)
* toplantı [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->