---
title: Top10
second_title: Aspose.Cells für .NET-API-Referenz
description: Beschreiben Sie die Top10 der bedingten Formatierungsregeln. Diese Regel zur bedingten Formatierung hebt Zellen hervor deren Werte in die obere N- oder untere N-Klammer fallen wie angegeben.
type: docs
weight: 6090
url: /de/net/aspose.cells/top10/
---
## Top10 class

Beschreiben Sie die Top10 der bedingten Formatierungsregeln. Diese Regel zur bedingten Formatierung hebt Zellen hervor, deren Werte in die obere N- oder untere N-Klammer fallen, wie angegeben.

```csharp
public class Top10
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Top10](top10)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsBottom](../../aspose.cells/top10/isbottom) { get; set; } | Abrufen oder Festlegen, ob eine „Top/Bottom n“-Regel eine „Bottom n“-Regel ist. Der Standardwert ist „false“. |
| [IsPercent](../../aspose.cells/top10/ispercent) { get; set; } | Abrufen oder Festlegen, ob eine „Top/Bottom n“-Regel eine „Top/Bottom n Prozent“-Regel ist. Der Standardwert ist „false“. |
| [Rank](../../aspose.cells/top10/rank) { get; set; } | Abrufen oder Festlegen des Werts von „n“ in einer bedingten Formatierungsregel „top/bottom n“. Wenn IsPercent wahr ist, muss der Wert zwischen 0 und 100 liegen. Andernfalls muss er zwischen 0 und 1000 liegen. Der Standardwert ist 10 . |

### Beispiele

```csharp

[C#]
//Instanziieren eines Workbook-Objekts
Workbook workbook = new Workbook();
Worksheet sheet = workbook.Worksheets[0];
 
//Fügt eine leere bedingte Formatierung hinzu
int index = sheet.ConditionalFormattings.Add();
FormatConditionCollection fcs = sheet.ConditionalFormattings[index];
 
//Legt den bedingten Formatbereich fest.
CellArea ca = CellArea.CreateCellArea(0, 0, 10, 10);
fcs.AddArea(ca);
 
//Bedingung hinzufügen.
int conditionIndex = fcs.AddCondition(FormatConditionType.Top10, OperatorType.None, null, null);   
//Setzt die Hintergrundfarbe.
FormatCondition fc = fcs[conditionIndex];
fc.Style.BackgroundColor = Color.Red;
Top10 top10 = fc.Top10;
//Setze die Top N 
top10.Rank = 5;  
//Speichern der Excel-Datei
workbook.Save("output.xls");

[VB.NET]

'Instanziieren eines Workbook-Objekts
Dim workbook As Workbook = New Workbook()
Dim sheet As Worksheet = workbook.Worksheets(0)
 
' Fügt eine leere bedingte Formatierung hinzu
Dim index As Integer = sheet.ConditionalFormattings.Add()
Dim fcs As FormatConditionCollection = sheet.ConditionalFormattings(index)
 
'Legt den bedingten Formatbereich fest.
Dim ca As CellArea = CellArea.CreateCellArea(0, 0, 10, 10)
fcs.AddArea(ca)
 
'Fügt Bedingung hinzu.
Dim conditionIndex As Integer = fcs.AddCondition(FormatConditionType.Top10, OperatorType.None, null, null);   
'Legt die Hintergrundfarbe fest.
Dim fc As FormatCondition = fcs(conditionIndex)
fc.Style.BackgroundColor = Color.Red
Dim top10 as Top10  = fc.Top10
'Stellen Sie die obere N ein 
top10.Rank = 5
'Speichern der Excel-Datei
workbook.Save("output.xls")
```

### Siehe auch

* namensraum [Aspose.Cells](../../aspose.cells)
* Montage [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->