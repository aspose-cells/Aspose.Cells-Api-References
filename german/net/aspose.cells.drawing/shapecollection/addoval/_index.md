---
title: AddOval
second_title: Aspose.Cells für .NET-API-Referenz
description: Fügt dem Arbeitsblatt ein Oval hinzu.
type: docs
weight: 200
url: /de/net/aspose.cells.drawing/shapecollection/addoval/
---
## ShapeCollection.AddOval method

Fügt dem Arbeitsblatt ein Oval hinzu.

```csharp
public Oval AddOval(int upperLeftRow, int top, int upperLeftColumn, int left, int height, int width)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| upperLeftRow | Int32 | Zeilenindex oben links. |
| top | Int32 | Stellt den vertikalen Versatz von Oval von seiner linken Zeile in Pixeleinheiten dar. |
| upperLeftColumn | Int32 | Spaltenindex oben links. |
| left | Int32 | Repräsentiert den horizontalen Versatz von Oval von seiner linken Spalte in Pixeleinheiten. |
| height | Int32 | Repräsentiert die Höhe von Oval in Pixeleinheiten. |
| width | Int32 | Repräsentiert die Breite des Ovals in Pixeleinheiten. |

### Rückgabewert

Ein ovales Objekt.

### Beispiele

```csharp

[C#]
// füge ein Oval hinzu
Oval oval = shapes.AddOval(1, 0, 1, 0, 50, 50);
```

### Siehe auch

* class [Oval](../../oval)
* class [ShapeCollection](../../shapecollection)
* namensraum [Aspose.Cells.Drawing](../../shapecollection)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->