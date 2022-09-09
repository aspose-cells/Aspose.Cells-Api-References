---
title: Column
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Rappresenta una singola colonna in un foglio di lavoro.
type: docs
weight: 1060
url: /it/net/aspose.cells/column/
---
## Column class

Rappresenta una singola colonna in un foglio di lavoro.

```csharp
public class Column
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GroupLevel](../../aspose.cells/column/grouplevel) { get; } | Ottiene il livello di gruppo della colonna. |
| [Index](../../aspose.cells/column/index) { get; } | Ottiene l'indice di questa colonna. |
| [IsCollapsed](../../aspose.cells/column/iscollapsed) { get; set; } | se la colonna è compressa |
| [IsHidden](../../aspose.cells/column/ishidden) { get; set; } | Indica se la colonna è nascosta. |
| [Style](../../aspose.cells/column/style) { get; } | Ottiene lo stile di questa colonna. |
| [Width](../../aspose.cells/column/width) { get; set; } | Ottiene e imposta la larghezza della colonna in unità di caratteri. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyStyle](../../aspose.cells/column/applystyle)(Style, StyleFlag) | Applica i formati per un'intera colonna. |

### Esempi

```csharp

[C#]

//Creazione di un'istanza di un oggetto cartella di lavoro
Workbook workbook = new Workbook();

//Ottenere il riferimento del primo foglio di lavoro
Worksheet worksheet = workbook.Worksheets[0];
Style style = workbook.CreateStyle();

//Impostazione del colore di sfondo su Blu
style.BackgroundColor = Color.Blue;

//Impostando il colore di primo piano su Rosso
style.ForegroundColor= Color.Red;

//impostazione del motivo di sfondo
style.Pattern = BackgroundType.DiagonalStripe;

//Nuovo stile bandiera
StyleFlag styleFlag = new StyleFlag();

//Imposta tutti gli stili
styleFlag.All = true;

//Ottieni la prima colonna
Column column = worksheet.Cells.Columns[0];

//Applica lo stile alla prima colonna
column.ApplyStyle(style, styleFlag);

//Salvataggio del file Excel
workbook.Save("book1.xls");

[VB.NET]

'Creazione di un'istanza di un oggetto Workbook
Dim workbook As Workbook = New Workbook()

'Ottenere il riferimento del primo foglio di lavoro
Dim worksheet As Worksheet = workbook.Worksheets(0)

Dim style As Style = workbook.CreateStyle()

'Impostare il colore di sfondo su Blu
style.BackgroundColor = Color.Blue

'Impostare il colore di primo piano su Rosso
style.ForegroundColor = Color.Red

'impostazione del motivo di sfondo
style.Pattern = BackgroundType.DiagonalStripe

'Nuovo stile bandiera
Dim styleFlag As New StyleFlag()

'Imposta tutti gli stili
styleFlag.All = True

'Ottieni la prima colonna
Dim column As Column = worksheet.Cells.Columns(0)

'Applica lo stile alla prima colonna
column.ApplyStyle(style, styleFlag)

'Salvataggio del file Excel
workbook.Save("book1.xls")
```

### Guarda anche

* spazio dei nomi [Aspose.Cells](../../aspose.cells)
* assemblea [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->