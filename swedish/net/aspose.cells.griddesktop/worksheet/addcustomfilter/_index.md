---
title: AddCustomFilter
second_title: Aspose.Cells för .NET API-referens
description: Lägg till anpassat filter för det angivna radintervallet från startrad till slutrad.
type: docs
weight: 450
url: /sv/net/aspose.cells.griddesktop/worksheet/addcustomfilter/
---
## AddCustomFilter(int, int, object[], GridFilterOperatorType[]) {#addcustomfilter}

Lägg till anpassat filter för det angivna radintervallet från startrad till slutrad.

```csharp
public void AddCustomFilter(int startrow, int startcolumn, object[] critiras, 
    GridFilterOperatorType[] filterOperatorTypes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startrow | Int32 | Startraden för filterintervallet |
| startcolumn | Int32 | Startkolumnen för filterintervallet |
| critiras | Object[] | Kriterimatrisen för kolumnerna, var och en gäller för varje kolumn |
| filterOperatorTypes | GridFilterOperatorType[] | Filteroperationstypens matris för kolumnerna, var och en gäller för varje kolumn |

### Se även

* enum [GridFilterOperatorType](../../../aspose.cells.griddesktop.data/gridfilteroperatortype)
* class [Worksheet](../../worksheet)
* namnutrymme [Aspose.Cells.GridDesktop](../../worksheet)
* hopsättning [Aspose.Cells.GridDesktop](../../../)

---

## AddCustomFilter(int, string) {#addcustomfilter_1}

Lägg till anpassat filter för den angivna raden.

```csharp
public void AddCustomFilter(int row, string critira)
```

### Anmärkningar

Filterkriteriesträngen. notera att vi använder , och ; som split char, så cellvärdet ska inte innehålla med de delade char nedan är kriteriesträngexemplen: //kolumn 0 med värdet 12.3 CELL0 = 12.3 //kolumn 1 med värdet ABC kolumn/kolumn_000d_CELL_000d värde 123 eller 456 eller ABC och kolumn 1 med värdet ABC CELL0 = 123,456,ABC; CELL1 = ABC

### Se även

* class [Worksheet](../../worksheet)
* namnutrymme [Aspose.Cells.GridDesktop](../../worksheet)
* hopsättning [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->