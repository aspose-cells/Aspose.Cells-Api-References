---
title: AddShape
second_title: Aspose.Cells för .NET API-referens
description: Lägger till en form i kalkylbladet.
type: docs
weight: 260
url: /sv/net/aspose.cells.drawing/shapecollection/addshape/
---
## ShapeCollection.AddShape method

Lägger till en form i kalkylbladet.

```csharp
public Shape AddShape(MsoDrawingType type, int upperLeftRow, int top, int upperLeftColumn, 
    int left, int height, int width)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | MsoDrawingType | Mso ritningstyp. |
| upperLeftRow | Int32 | Övre vänstra radens index. |
| top | Int32 | Representerar den vertikala förskjutningen av Shape från dess vänstra rad, i pixelenhet. |
| upperLeftColumn | Int32 | Övre vänstra kolumnindex. |
| left | Int32 | Representerar den horisontella förskjutningen av Shape från dess vänstra kolumn, i pixelenhet. |
| height | Int32 | Representerar höjden på Shape, i pixelenhet. |
| width | Int32 | Representerar bredden på Shape, i pixelenhet. |

### Returvärde

Ett Shape-objekt.

### Anmärkningar

Typen kunde inte vara Chart/Comment/Picture/OleObject/Polygon/DialogBox

### Exempel

```csharp

[C#]
//Lägg till en form av den angivna typen
Shape shapeByType = shapes.AddShape(MsoDrawingType.CellsDrawing, 1, 0, 1, 0, 100, 50);
```

### Se även

* class [Shape](../../shape)
* enum [MsoDrawingType](../../msodrawingtype)
* class [ShapeCollection](../../shapecollection)
* namnutrymme [Aspose.Cells.Drawing](../../shapecollection)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->