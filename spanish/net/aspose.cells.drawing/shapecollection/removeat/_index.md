---
title: RemoveAt
second_title: Referencia de API de Aspose.Cells para .NET
description: Eliminar la forma.
type: docs
weight: 430
url: /es/net/aspose.cells.drawing/shapecollection/removeat/
---
## ShapeCollection.RemoveAt method

Eliminar la forma.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de la forma. |

### Ejemplos

```csharp

[C#]
//añadir primera forma
shapes.AddRectangle(2, 0, 2, 0, 50, 50);
//añadir segunda forma
shapes.AddRectangle(6, 0, 2, 0, 30, 30);

//retirar 
shapes.RemoveAt(0);

```

### Ver también

* class [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Cells.Drawing](../../shapecollection)
* asamblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->