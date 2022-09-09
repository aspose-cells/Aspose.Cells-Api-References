---
title: OriginalWidth
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Ottiene la larghezza originale dellimmagine.
type: docs
weight: 130
url: /it/net/aspose.cells.drawing/picture/originalwidth/
---
## Picture.OriginalWidth property

Ottiene la larghezza originale dell'immagine.

```csharp
public int OriginalWidth { get; }
```

### Esempi

```csharp

[C#]
//Creazione di un'istanza di un oggetto cartella di lavoro
Workbook workbook = new Workbook();
Worksheet worksheet = workbook.Worksheets[0];
//Aggiunta di un'immagine nella posizione di una cella i cui indici di riga e colonna sono 1 nel foglio di lavoro. È la cella "B2".
int imgIndex = worksheet.Pictures.Add(1, 1, "example.jpeg");
//Ottieni l'oggetto immagine inserito
Picture pic = worksheet.Pictures[imgIndex];
//Ottiene la larghezza originale dell'immagine.
int picWidth = pic.OriginalWidth;
//Salva il file excel.
workbook.Save("result.xlsx");
```

### Guarda anche

* class [Picture](../../picture)
* spazio dei nomi [Aspose.Cells.Drawing](../../picture)
* assemblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->