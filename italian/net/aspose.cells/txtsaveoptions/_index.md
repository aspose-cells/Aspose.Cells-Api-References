---
title: TxtSaveOptions
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Rappresenta le opzioni di salvataggio per csv/delimitato da tabulazioni/altro formato di testo.
type: docs
weight: 6130
url: /it/net/aspose.cells/txtsaveoptions/
---
## TxtSaveOptions class

Rappresenta le opzioni di salvataggio per csv/delimitato da tabulazioni/altro formato di testo.

```csharp
public class TxtSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TxtSaveOptions](txtsaveoptions#constructor)() | Crea opzioni di salvataggio del file di testo. |
| [TxtSaveOptions](txtsaveoptions#constructor_1)(SaveFormat) | Crea opzioni di salvataggio del file di testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CachedFileFolder](../../aspose.cells/saveoptions/cachedfilefolder) { get; set; } | La cartella dei file nella cache viene utilizzata per memorizzare dati di grandi dimensioni. |
| [ClearData](../../aspose.cells/saveoptions/cleardata) { get; set; } | Rendi vuota la cartella di lavoro dopo aver salvato il file. |
| [CreateDirectory](../../aspose.cells/saveoptions/createdirectory) { get; set; } | Se true e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file. |
| [Encoding](../../aspose.cells/txtsaveoptions/encoding) { get; set; } | Ottiene e imposta la codifica predefinita. |
| [ExportAllSheets](../../aspose.cells/txtsaveoptions/exportallsheets) { get; set; } | Indica se esportare tutti i fogli nel file di testo. Se è falso, esportare solo il foglio attivo, proprio come MS Excel. |
| [ExportArea](../../aspose.cells/txtsaveoptions/exportarea) { get; set; } | L'intervallo di celle da esportare. |
| [ExportQuotePrefix](../../aspose.cells/txtsaveoptions/exportquoteprefix) { get; set; } | Indica se il segno di virgoletta singola deve essere esportato come parte del valore di una cella quando[`QuotePrefix`](../style/quoteprefix) è vero per questo. L'impostazione predefinita è false. |
| [FormatStrategy](../../aspose.cells/txtsaveoptions/formatstrategy) { get; set; } | Ottiene e imposta la strategia di formattazione durante l'esportazione del valore della cella come stringa. |
| [KeepSeparatorsForBlankRow](../../aspose.cells/txtsaveoptions/keepseparatorsforblankrow) { get; set; } | Indica se i separatori devono essere emessi per la riga vuota. Il valore predefinito è false, quindi per impostazione predefinita il contenuto della riga vuota sarà vuoto. |
| [LightCellsDataProvider](../../aspose.cells/txtsaveoptions/lightcellsdataprovider) { get; set; } | Il provider di dati per fornire i dati delle celle per il salvataggio della cartella di lavoro in modalità luce. |
| [MergeAreas](../../aspose.cells/saveoptions/mergeareas) { get; set; } | Indica se unire le aree di formattazione condizionale e validazione prima di salvare il file. |
| [QuoteType](../../aspose.cells/txtsaveoptions/quotetype) { get; set; } | Ottiene o imposta come citare i valori nel file di testo esportato. |
| [RefreshChartCache](../../aspose.cells/saveoptions/refreshchartcache) { get; set; } | Indica se aggiornare i dati della cache del grafico |
| [SaveFormat](../../aspose.cells/saveoptions/saveformat) { get; } | Ottiene il formato del file di salvataggio. |
| [Separator](../../aspose.cells/txtsaveoptions/separator) { get; set; } | Ottiene e imposta char Delimitatore del file di testo. |
| [SeparatorString](../../aspose.cells/txtsaveoptions/separatorstring) { get; set; } | Ottiene e imposta un valore stringa come separatore. |
| [SortExternalNames](../../aspose.cells/saveoptions/sortexternalnames) { get; set; } | Indica se ordinare i nomi definiti esterni prima di salvare il file. |
| [SortNames](../../aspose.cells/saveoptions/sortnames) { get; set; } | Indica se ordinare i nomi definiti prima di salvare il file. |
| [TrimLeadingBlankRowAndColumn](../../aspose.cells/txtsaveoptions/trimleadingblankrowandcolumn) { get; set; } | Indica se le righe e le colonne vuote iniziali devono essere tagliate come fa ms excel. L'impostazione predefinita è true. |
| [TrimTailingBlankCells](../../aspose.cells/txtsaveoptions/trimtailingblankcells) { get; set; } | Indica se le celle vuote in coda in una riga devono essere tagliate. L'impostazione predefinita è false. |
| [UpdateSmartArt](../../aspose.cells/saveoptions/updatesmartart) { get; set; } | Indica se aggiornare l'impostazione Smart Art. Il valore predefinito è false. |
| [ValidateMergedAreas](../../aspose.cells/saveoptions/validatemergedareas) { get; set; } | Indica se convalidare le celle unite prima di salvare il file. |
| [WarningCallback](../../aspose.cells/saveoptions/warningcallback) { get; set; } | Ottiene o imposta la richiamata di avviso. |

### Guarda anche

* class [SaveOptions](../saveoptions)
* spazio dei nomi [Aspose.Cells](../../aspose.cells)
* assemblea [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->