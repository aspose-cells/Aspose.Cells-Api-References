---
title: Subtotal
second_title: Aspose.Cells för .NET API-referens
description: Skapar delsummor för intervallet.
type: docs
weight: 1310
url: /sv/net/aspose.cells/cells/subtotal/
---
## Subtotal(CellArea, int, ConsolidationFunction, int[]) {#subtotal}

Skapar delsummor för intervallet.

```csharp
public void Subtotal(CellArea ca, int groupBy, ConsolidationFunction function, int[] totalList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ca | CellArea | Räckvidden |
| groupBy | Int32 | Fältet att gruppera efter, som en nollbaserad heltalsoffset |
| function | ConsolidationFunction | Subtotalfunktionen. |
| totalList | Int32[] | En matris med nollbaserade fältförskjutningar, som indikerar de fält till vilka delsummorna läggs till. |

### Se även

* struct [CellArea](../../cellarea)
* enum [ConsolidationFunction](../../consolidationfunction)
* class [Cells](../../cells)
* namnutrymme [Aspose.Cells](../../cells)
* hopsättning [Aspose.Cells](../../../)

---

## Subtotal(CellArea, int, ConsolidationFunction, int[], bool, bool, bool) {#subtotal_1}

Skapar delsummor för intervallet.

```csharp
public void Subtotal(CellArea ca, int groupBy, ConsolidationFunction function, int[] totalList, 
    bool replace, bool pageBreaks, bool summaryBelowData)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ca | CellArea | Räckvidden |
| groupBy | Int32 | Fältet att gruppera efter, som en nollbaserad heltalsoffset |
| function | ConsolidationFunction | Subtotalfunktionen. |
| totalList | Int32[] | En matris med nollbaserade fältförskjutningar, som indikerar de fält till vilka delsummorna läggs till. |
| replace | Boolean | Anger om de nuvarande delsummorna ersätts |
| pageBreaks | Boolean | Anger om man lägger till sidbrytning mellan grupper |
| summaryBelowData | Boolean | Anger om du lägger till sammanfattning nedanför data. |

### Se även

* struct [CellArea](../../cellarea)
* enum [ConsolidationFunction](../../consolidationfunction)
* class [Cells](../../cells)
* namnutrymme [Aspose.Cells](../../cells)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->