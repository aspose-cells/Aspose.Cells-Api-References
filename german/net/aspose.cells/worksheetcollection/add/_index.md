---
title: Add
second_title: Aspose.Cells für .NET-API-Referenz
description: Fügt der Sammlung ein Arbeitsblatt hinzu.
type: docs
weight: 170
url: /de/net/aspose.cells/worksheetcollection/add/
---
## Add(SheetType) {#add_2}

Fügt der Sammlung ein Arbeitsblatt hinzu.

```csharp
public int Add(SheetType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | SheetType | Arbeitsblatttyp. |

### Rückgabewert

[`Worksheet`](../../worksheet) Objektindex.

### Beispiele

```csharp
[C#]
Workbook workbook = new Workbook();
workbook.Worksheets.Add(SheetType.Chart);
Cells cells = workbook.Worksheets[0].Cells;
cells["c2"].PutValue(5000);
cells["c3"].PutValue(3000);
cells["c4"].PutValue(4000);
cells["c5"].PutValue(5000);
cells["c6"].PutValue(6000);
ChartCollection charts = workbook.Worksheets[1].Charts;
int chartIndex = charts.Add(ChartType.Column, 10,10,20,20);
Chart chart = charts[chartIndex];
chart.NSeries.Add("Sheet1!C2:C6", true);

[Visual Basic]
Dim workbook As Workbook =  New Workbook() 
workbook.Worksheets.Add(SheetType.Chart)
Dim cells As Cells = workbook.Worksheets(0).Cells 
cells("c2").PutValue(5000)
cells("c3").PutValue(3000)
cells("c4").PutValue(4000)
cells("c5").PutValue(5000)
cells("c6").PutValue(6000)
Dim charts As ChartCollection = workbook.Worksheets(1).Charts
Dim chartIndex As Integer = charts.Add(ChartType.Column,10,10,20,20) 
Dim chart As Chart = charts(chartIndex) 
chart.NSeries.Add("Sheet1!C2:C6", True)
```

### Siehe auch

* enum [SheetType](../../sheettype)
* class [WorksheetCollection](../../worksheetcollection)
* namensraum [Aspose.Cells](../../worksheetcollection)
* Montage [Aspose.Cells](../../../)

---

## Add() {#add_1}

Fügt der Sammlung ein Arbeitsblatt hinzu.

```csharp
public int Add()
```

### Rückgabewert

[`Worksheet`](../../worksheet) Objektindex.

### Siehe auch

* class [WorksheetCollection](../../worksheetcollection)
* namensraum [Aspose.Cells](../../worksheetcollection)
* Montage [Aspose.Cells](../../../)

---

## Add(string) {#add}

Fügt der Sammlung ein Arbeitsblatt hinzu.

```csharp
public Worksheet Add(string sheetName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sheetName | String | Arbeitsblattname |

### Rückgabewert

[`Worksheet`](../../worksheet) Objekt.

### Siehe auch

* class [Worksheet](../../worksheet)
* class [WorksheetCollection](../../worksheetcollection)
* namensraum [Aspose.Cells](../../worksheetcollection)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->