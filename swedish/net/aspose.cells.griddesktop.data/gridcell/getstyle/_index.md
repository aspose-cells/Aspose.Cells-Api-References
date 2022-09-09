---
title: GetStyle
second_title: Aspose.Cells för .NET API-referens
description: Får cellstil. När du ändrar stil bör du anropa SetStyle-metoden för att ställa in stil till cell.
type: docs
weight: 280
url: /sv/net/aspose.cells.griddesktop.data/gridcell/getstyle/
---
## GridCell.GetStyle method

Får cellstil. När du ändrar stil bör du anropa "SetStyle"-metoden, för att ställa in stil till cell.

```csharp
public Style GetStyle()
```

### Returvärde

returnera kopia av cellstil.

### Exempel

```csharp
[C#]
Style style = sheet.GetCell(0, 0).GetStyle();
style.CellLocked = true;
style.VAlignment = VerticalAlignmentType.Top;
...
sheet.GetCell(0, 0).SetStyle(style);

[Visual Basic]
Dim style As Style =  sheet.GetCell(0,0).GetStyle() 
style.CellLocked = True
style.VAlignment = VerticalAlignmentType.Top
...
sheet.GetCell(0, 0).SetStyle(style)

```

### Se även

* class [Style](../../../aspose.cells.griddesktop/style)
* class [GridCell](../../gridcell)
* namnutrymme [Aspose.Cells.GridDesktop.Data](../../gridcell)
* hopsättning [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->