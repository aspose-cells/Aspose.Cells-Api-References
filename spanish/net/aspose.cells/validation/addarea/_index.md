---
title: AddArea
second_title: Referencia de API de Aspose.Cells para .NET
description: Aplica la validación al área.
type: docs
weight: 170
url: /es/net/aspose.cells/validation/addarea/
---
## AddArea(CellArea) {#addarea}

Aplica la validación al área.

```csharp
public void AddArea(CellArea cellArea)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| cellArea | CellArea | La zona. |

### Observaciones

Es equivalente a usar[`AddArea`](../addarea) con verificación de intersección y borde.

### Ver también

* struct [CellArea](../../cellarea)
* class [Validation](../../validation)
* espacio de nombres [Aspose.Cells](../../validation)
* asamblea [Aspose.Cells](../../../)

---

## AddArea(CellArea, bool, bool) {#addarea_1}

Aplica la validación al área.

```csharp
public void AddArea(CellArea cellArea, bool checkIntersection, bool checkEdge)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| cellArea | CellArea | La zona. |
| checkIntersection | Boolean | Si se verifica la intersección del área dada con las áreas de validaciones existentes. Si se ha aplicado una validación en el área dada (o parte de ella), entonces la validación existente debe eliminarse primero del área dada. De lo contrario, se puede causar corrupción para las Validaciones generadas. Si el usuario está seguro de que el área agregada no intersecta con ningún área existente, este parámetro se puede configurar como falso para considerar el rendimiento. |
| checkEdge | Boolean | Si verifica el borde de las áreas aplicadas de esta validación. La configuración interna de la validación depende del rango superior izquierdo de sus rangos aplicados, por lo que si el área dada se convertirá en el nuevo rango superior izquierdo de los rangos aplicados, la configuración interna debe ser cambiado y reconstruido; de lo contrario, se pueden producir resultados inesperados. Si el usuario está seguro de que el área agregada no es la de arriba a la izquierda, este parámetro se puede configurar como falso para considerar el rendimiento. |

### Observaciones

En este método, eliminaremos todas las validaciones antiguas en un área determinada. Para el rango superior izquierdo de los rangos aplicados de Validación, en primer lugar, su StartRow es la más pequeña, en segundo lugar, su StartColumn es la más pequeña de aquellas áreas que tienen la misma StartRow más pequeña .

### Ver también

* struct [CellArea](../../cellarea)
* class [Validation](../../validation)
* espacio de nombres [Aspose.Cells](../../validation)
* asamblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->