---
title: Subtotal
second_title: Aspose.Cells für .NET-API-Referenz
description: Erstellt Zwischensummen für den Bereich.
type: docs
weight: 1310
url: /de/net/aspose.cells/cells/subtotal/
---
## Subtotal(CellArea, int, ConsolidationFunction, int[]) {#subtotal}

Erstellt Zwischensummen für den Bereich.

```csharp
public void Subtotal(CellArea ca, int groupBy, ConsolidationFunction function, int[] totalList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ca | CellArea | Die Reichweite |
| groupBy | Int32 | Das zu gruppierende Feld als nullbasierter ganzzahliger Offset |
| function | ConsolidationFunction | Die Zwischensummenfunktion. |
| totalList | Int32[] | Ein Array von nullbasierten Feld-Offsets, das die Felder angibt, zu denen die Zwischensummen hinzugefügt werden. |

### Siehe auch

* struct [CellArea](../../cellarea)
* enum [ConsolidationFunction](../../consolidationfunction)
* class [Cells](../../cells)
* namensraum [Aspose.Cells](../../cells)
* Montage [Aspose.Cells](../../../)

---

## Subtotal(CellArea, int, ConsolidationFunction, int[], bool, bool, bool) {#subtotal_1}

Erstellt Zwischensummen für den Bereich.

```csharp
public void Subtotal(CellArea ca, int groupBy, ConsolidationFunction function, int[] totalList, 
    bool replace, bool pageBreaks, bool summaryBelowData)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ca | CellArea | Die Reichweite |
| groupBy | Int32 | Das zu gruppierende Feld als nullbasierter ganzzahliger Offset |
| function | ConsolidationFunction | Die Zwischensummenfunktion. |
| totalList | Int32[] | Ein Array von nullbasierten Feld-Offsets, das die Felder angibt, zu denen die Zwischensummen hinzugefügt werden. |
| replace | Boolean | Gibt an, ob die aktuellen Zwischensummen ersetzt werden sollen |
| pageBreaks | Boolean | Gibt an, ob ein Seitenumbruch zwischen Gruppen hinzugefügt wird |
| summaryBelowData | Boolean | Gibt an, ob eine Zusammenfassung unter den Daten hinzugefügt werden soll. |

### Siehe auch

* struct [CellArea](../../cellarea)
* enum [ConsolidationFunction](../../consolidationfunction)
* class [Cells](../../cells)
* namensraum [Aspose.Cells](../../cells)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->