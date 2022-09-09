---
title: AddCondition
second_title: Referencia de API de Aspose.Cells para .NET
description: Agrega una condición de formato.
type: docs
weight: 60
url: /es/net/aspose.cells/formatconditioncollection/addcondition/
---
## AddCondition(FormatConditionType, OperatorType, string, string) {#addcondition_1}

Agrega una condición de formato.

```csharp
public int AddCondition(FormatConditionType type, OperatorType operatorType, string formula1, 
    string formula2)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | FormatConditionType | de formato condicional. Podría ser uno de los miembros de FormatConditionType. |
| operatorType | OperatorType | La comparación[`OperatorType`](../../operatortype). Podría ser uno de los miembros de OperatorType. |
| formula1 | String | El valor o la expresión asociada con el formato condicional. Si el valor de entrada comienza con '=', se tomará como fórmula. De lo contrario, se tomará como valor simple (texto, número, bool). Para el valor de texto que comienza con '=', el usuario puede ingresarlo como fórmula en formato: "=\"=...\"". |
| formula2 | String | El valor o la expresión asociada con el formato condicional. El formato de entrada es el mismo que con la fórmula 1 |

### Valor_devuelto

Índice de objeto de condición de formato;

### Ver también

* enum [FormatConditionType](../../formatconditiontype)
* enum [OperatorType](../../operatortype)
* class [FormatConditionCollection](../../formatconditioncollection)
* espacio de nombres [Aspose.Cells](../../formatconditioncollection)
* asamblea [Aspose.Cells](../../../)

---

## AddCondition(FormatConditionType) {#addcondition}

Agregar una condición de formato.

```csharp
public int AddCondition(FormatConditionType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | FormatConditionType | Tipo de condición de formato. |

### Valor_devuelto

Índice de objeto de condición de formato;

### Ver también

* enum [FormatConditionType](../../formatconditiontype)
* class [FormatConditionCollection](../../formatconditioncollection)
* espacio de nombres [Aspose.Cells](../../formatconditioncollection)
* asamblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->