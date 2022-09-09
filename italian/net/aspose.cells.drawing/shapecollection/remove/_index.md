---
title: Remove
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Rimuovi la forma.
type: docs
weight: 420
url: /it/net/aspose.cells.drawing/shapecollection/remove/
---
## ShapeCollection.Remove method

Rimuovi la forma.

```csharp
public void Remove(Shape shape)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | Shape |  |

### Esempi

```csharp

[C#]
//aggiungi la prima forma
shapes.AddRectangle(2, 0, 2, 0, 50, 50);
//aggiungi la seconda forma
shapes.AddRectangle(6, 0, 2, 0, 30, 30);

//ottengo la forma
Shape s = shapes["Rectangle 1"];// o forme[0];
if (s != null)
{
    //rimuovere 
    shapes.Remove(s);
}
```

### Guarda anche

* class [Shape](../../shape)
* class [ShapeCollection](../../shapecollection)
* spazio dei nomi [Aspose.Cells.Drawing](../../shapecollection)
* assemblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->