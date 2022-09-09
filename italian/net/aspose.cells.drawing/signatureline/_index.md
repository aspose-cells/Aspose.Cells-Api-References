---
title: SignatureLine
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Rappresenta la linea della firma.
type: docs
weight: 2770
url: /it/net/aspose.cells.drawing/signatureline/
---
## SignatureLine class

Rappresenta la linea della firma.

```csharp
public class SignatureLine
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SignatureLine](signatureline)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllowComments](../../aspose.cells.drawing/signatureline/allowcomments) { get; set; } | Indica se è possibile allegare commenti. |
| [Email](../../aspose.cells.drawing/signatureline/email) { get; set; } | Ottiene e imposta l'e-mail del cantante. |
| [Id](../../aspose.cells.drawing/signatureline/id) { get; set; } | Ottiene o imposta l'identificatore per questa riga della firma. |
| [Instructions](../../aspose.cells.drawing/signatureline/instructions) { get; set; } | Ottiene e imposta il testo mostrato all'utente al momento della firma. |
| [IsLine](../../aspose.cells.drawing/signatureline/isline) { get; set; } | Indica se si tratta di una riga della firma. |
| [ProviderId](../../aspose.cells.drawing/signatureline/providerid) { get; set; } | Ottiene e imposta l'ID del provider di firma. |
| [ShowSignedDate](../../aspose.cells.drawing/signatureline/showsigneddate) { get; set; } | Indica se mostrare la data firmata. |
| [Signer](../../aspose.cells.drawing/signatureline/signer) { get; set; } | Ottiene e imposta il firmatario. |
| [Title](../../aspose.cells.drawing/signatureline/title) { get; set; } | Ottiene e imposta il titolo del cantante. |

### Esempi

```csharp

[C#]

//Creazione di un'istanza di un oggetto cartella di lavoro
Workbook workbook = new Workbook();
Worksheet worksheet = workbook.Worksheets[0];

//Aggiunta di un'immagine
int imgIndex = worksheet.Pictures.Add(1, 1, "sample.png");
Picture pic = worksheet.Pictures[imgIndex];
// Crea un oggetto linea di firma
SignatureLine s = new SignatureLine();
s.Signer = "Simon Zhao";
s.Title = "Development Lead";
s.Email = "Simon.Zhao@aspose.com";
// Assegna l'oggetto linea di firma alla proprietà Picture.SignatureLine
pic.SignatureLine = s;

//fai i tuoi affari

//Salva il file excel.
workbook.Save("result.xlsx");
```

### Guarda anche

* spazio dei nomi [Aspose.Cells.Drawing](../../aspose.cells.drawing)
* assemblea [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->