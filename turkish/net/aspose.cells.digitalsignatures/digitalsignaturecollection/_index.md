---
title: DigitalSignatureCollection
second_title: Aspose.Cells for .NET API Referansı
description: Bir belgeye eklenmiş bir dijital imza koleksiyonu sağlar.
type: docs
weight: 1400
url: /tr/net/aspose.cells.digitalsignatures/digitalsignaturecollection/
---
## DigitalSignatureCollection class

Bir belgeye eklenmiş bir dijital imza koleksiyonu sağlar.

```csharp
public class DigitalSignatureCollection : IEnumerable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DigitalSignatureCollection](digitalsignaturecollection)() | DigitalSignatureCollection'ın yapıcısı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../aspose.cells.digitalsignatures/digitalsignaturecollection/add)(DigitalSignature) | DigitalSignatureCollection'a bir imza ekleyin. |
| [GetEnumerator](../../aspose.cells.digitalsignatures/digitalsignaturecollection/getenumerator)() | DigitalSignatureCollection için numaralandırıcıyı alın, bu numaralandırıcı, collection üzerinde yinelemeye izin verir |

### Örnekler

Aşağıdaki örnek, dijital imzanın nasıl oluşturulacağını gösterir

```csharp
[C#]
internal void ValidateSignature()
{
   Workbook wb = new Workbook(@"newfile.xlsx");
   //wb.IsDigitallySigned, çalışma kitabı zaten imzalanmışsa doğrudur.
   System.Console.WriteLine(wb.IsDigitallySigned);
   //çalışma kitabından digitalSignature koleksiyonunu al
   DigitalSignatureCollection dsc = wb.GetDigitalSignature();
   foreach (DigitalSignature ds in dsc)
   {
       System.Console.WriteLine(ds.Comments);
       System.Console.WriteLine(ds.SignTime);
       System.Console.WriteLine(ds.IsValid);
   }
}
internal void SignSignature()
{
   //dsc imza koleksiyonu, imzalamak için gereken bir veya daha fazla imza içerir
   DigitalSignatureCollection dsc = new DigitalSignatureCollection();
   //sertifika özel anahtar içermelidir, sertifika dosyasından veya Windows sertifika koleksiyonundan oluşturulabilir.
   //123456, sertifikanın şifresidir
   X509Certificate2 cert = new X509Certificate2("mykey2.pfx", "123456");
   DigitalSignature ds = new DigitalSignature(cert, "test for sign", DateTime.Now);
   dsc.Add(ds);
   Workbook wb = new Workbook();
   //wb.SetDigitalSignature tüm imzaları dsc'de imzala
   wb.SetDigitalSignature(dsc);
   wb.Save(@"newfile.xlsx");
}

[Visual Basic]
   Sub ValidateSignature()
   Dim workbook As Workbook = New Workbook("newfile.xlsx")
   'Workbook.IsDigitallySigned, çalışma kitabı zaten imzalanmışsa doğrudur.
   System.Console.WriteLine(workbook.IsDigitallySigned)
   'çalışma kitabından digitalSignature koleksiyonunu alın
   Dim dsc As DigitalSignatureCollection = workbook.GetDigitalSignature()
   Dim ds As DigitalSignature
   For Each ds In dsc
       System.Console.WriteLine(ds.Comments)
       System.Console.WriteLine(ds.SignTime)
       System.Console.WriteLine(ds.IsValid)
   Next
End Sub

Sub SignSignature()
   'dsc imza koleksiyonudur, imzalamak için gereken bir veya daha fazla imza içerir
   Dim dsc As DigitalSignatureCollection = New DigitalSignatureCollection()
   'sertifika özel anahtar içermelidir, sertifika dosyasından veya Windows sertifika koleksiyonundan oluşturulabilir.
   Dim cert As X509Certificate2 = New X509Certificate2("mykey2.pfx", "123456")
   'sertifika, imza amacı ve imza zamanı ile bir imza oluşturun
   Dim ds As DigitalSignature = New DigitalSignature(cert, "test for sign", DateTime.Now)
   dsc.Add(ds)
   Dim workbook As Workbook = New Workbook()
   'workbook.SetDigitalSignature dsc'deki tüm imzaları imzala
   workbook.SetDigitalSignature(dsc)
   workbook.Save("newfile.xlsx")
End Sub
```

### Ayrıca bakınız

* ad alanı [Aspose.Cells.DigitalSignatures](../../aspose.cells.digitalsignatures)
* toplantı [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->