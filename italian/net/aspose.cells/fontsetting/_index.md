---
title: FontSetting
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Rappresenta un intervallo di caratteri allinterno del testo della cella.
type: docs
weight: 3520
url: /it/net/aspose.cells/fontsetting/
---
## FontSetting class

Rappresenta un intervallo di caratteri all'interno del testo della cella.

```csharp
public class FontSetting
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FontSetting](fontsetting)(int, int, WorksheetCollection) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Font](../../aspose.cells/fontsetting/font) { get; } | Restituisce il carattere di questo oggetto. |
| [Length](../../aspose.cells/fontsetting/length) { get; } | Ottiene la lunghezza dei caratteri. |
| [StartIndex](../../aspose.cells/fontsetting/startindex) { get; } | Ottiene l'indice iniziale dei caratteri. |
| [TextOptions](../../aspose.cells/fontsetting/textoptions) { get; } | Restituisce le opzioni di testo. |
| virtual [Type](../../aspose.cells/fontsetting/type) { get; } | Ottiene il tipo di nodo di testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetWordArtStyle](../../aspose.cells/fontsetting/setwordartstyle)(PresetWordArtStyle) | Imposta lo stile WordArt predefinito. |

### Esempi

```csharp

[C#]

//Creazione di un'istanza di un oggetto cartella di lavoro
Workbook workbook = new Workbook();

//Aggiunta di un nuovo foglio di lavoro all'oggetto Excel
workbook.Worksheets.Add();

//Ottenere il riferimento del foglio di lavoro appena aggiunto passando il relativo indice del foglio
Worksheet worksheet = workbook.Worksheets[0];

//Accesso alla cella "A1" dal foglio di lavoro
Aspose.Cells.Cell cell = worksheet.Cells["A1"];

//Aggiunta di valore alla cella "A1".
cell.PutValue("Visit Aspose!");

//ottengo il personaggio
FontSetting charactor = cell.Characters(6, 7);

//Impostazione del carattere dei caratteri selezionati in grassetto
charactor.Font.IsBold = true;

//Impostazione del colore del carattere dei caratteri selezionati su blu
charactor.Font.Color = Color.Blue;

//Salvataggio del file Excel
workbook.Save("book1.xls");

[VB.NET]

'Creazione di un'istanza di un oggetto Workbook
Dim workbook As Workbook = New Workbook()

'Aggiunta di un nuovo foglio di lavoro all'oggetto Excel
workbook.Worksheets.Add()

'Ottenere il riferimento del foglio di lavoro appena aggiunto passando il suo indice del foglio
Dim worksheet As Worksheet = workbook.Worksheets(0)

'Accessing the "A1" cell from the worksheet
Dim cell As Aspose.Cells.Cell = worksheet.Cells("A1")

'Adding some value to the "A1" cell
cell.PutValue("Visit Aspose!")

'ottenere il carattere
Dim charactor As FontSetting = cell.Characters(6, 7)

'Impostazione del carattere dei caratteri selezionati in grassetto
charactor.Font.IsBold = True

'Impostazione del colore del carattere dei caratteri selezionati su blu
charactor.Font.Color = Color.Blue

'Salvataggio del file Excel
workbook.Save("book1.xls")
 
```

### Guarda anche

* spazio dei nomi [Aspose.Cells](../../aspose.cells)
* assemblea [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->