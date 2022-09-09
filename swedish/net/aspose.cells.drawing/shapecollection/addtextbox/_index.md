---
title: AddTextBox
second_title: Aspose.Cells för .NET API-referens
description: Lägger till en textruta i kalkylbladet.
type: docs
weight: 310
url: /sv/net/aspose.cells.drawing/shapecollection/addtextbox/
---
## ShapeCollection.AddTextBox method

Lägger till en textruta i kalkylbladet.

```csharp
public TextBox AddTextBox(int upperLeftRow, int top, int upperLeftColumn, int left, int height, 
    int width)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| upperLeftRow | Int32 | Övre vänstra radens index. |
| top | Int32 | Representerar den vertikala förskjutningen av textrutan från dess vänstra rad, i pixelenhet. |
| upperLeftColumn | Int32 | Övre vänstra kolumnindex. |
| left | Int32 | Representerar den horisontella förskjutningen av textrutan från dess vänstra kolumn, i pixelenhet. |
| height | Int32 | Representerar höjden på textrutan, i pixelenhet. |
| width | Int32 | Representerar bredden på textrutan, i pixelenhet. |

### Returvärde

A[`TextBox`](../../textbox) objekt.

### Exempel

```csharp

[C#]

//lägg till en textruta
TextBox textBox = shapes.AddTextBox(1, 0, 1, 0, 100, 50);
```

### Se även

* class [TextBox](../../textbox)
* class [ShapeCollection](../../shapecollection)
* namnutrymme [Aspose.Cells.Drawing](../../shapecollection)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->