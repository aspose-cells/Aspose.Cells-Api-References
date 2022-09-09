---
title: CopyCommentsInRange
second_title: Aspose.Cells für .NET-API-Referenz
description: Alle Kommentare im Bereich kopieren.
type: docs
weight: 370
url: /de/net/aspose.cells.drawing/shapecollection/copycommentsinrange/
---
## ShapeCollection.CopyCommentsInRange method

Alle Kommentare im Bereich kopieren.

```csharp
public void CopyCommentsInRange(ShapeCollection shapes, CellArea ca, int destRow, int destColumn)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | ShapeCollection | Die Quellformen. |
| ca | CellArea | Der Quellbereich. |
| destRow | Int32 | Die Startreihe des Zielbereichs. |
| destColumn | Int32 | Die Startspalte des Zielbereichs. |

### Beispiele

```csharp

[C#]
CommentCollection comments = workbook.Worksheets[0].Comments;

//Kommentar zu Zelle A1 hinzufügen
int commentIndex = comments.Add(0, 0);
Comment comment = comments[commentIndex];
comment.Note = "First note.";
comment.Font.Name = "Times New Roman";

//Kommentar zu Zelle B2 hinzufügen
comments.Add("B2");
comment = comments["B2"];
comment.Note = "Second note.";

CellArea area1 = new CellArea();
area1.StartColumn = 1;
area1.StartRow = 1;
area1.EndColumn = 5;
area1.EndRow = 4;

//Kopieren
shapes.CopyCommentsInRange(shapes, area1, 5, 1);

```

### Siehe auch

* struct [CellArea](../../../aspose.cells/cellarea)
* class [ShapeCollection](../../shapecollection)
* namensraum [Aspose.Cells.Drawing](../../shapecollection)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->