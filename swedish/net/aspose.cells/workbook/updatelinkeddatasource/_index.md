---
title: UpdateLinkedDataSource
second_title: Aspose.Cells för .NET API-referens
description: Om den här arbetsboken innehåller externa länkar till andra datakällor kommer Aspose.Cells att försöka hämta de senaste uppgifterna.
type: docs
weight: 660
url: /sv/net/aspose.cells/workbook/updatelinkeddatasource/
---
## Workbook.UpdateLinkedDataSource method

Om den här arbetsboken innehåller externa länkar till andra datakällor, kommer Aspose.Cells att försöka hämta de senaste uppgifterna.

```csharp
public void UpdateLinkedDataSource(Workbook[] externalWorkbooks)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| externalWorkbooks | Workbook[] | Externa arbetsböcker refereras av den här arbetsboken. Om den är null öppnar vi de externt länkade filerna direkt.. Om den inte är null, kommer vi att kontrollera om den externa länken i arrayen först; om inte, öppnar vi de externt länkade filerna igen. |

### Anmärkningar

Om metoden inte anropas innan formler beräknas, kommer Aspose.Cells att använda den tidigare informationen (cachelagrad i filen); Vänligen ställ in CellsHelper.StartupPath,CellsHelper.AltStartPath,CellsHelper.LibraryPath. Och vänligen ställ in Workbook.FilePath om denna arbetsbok är från en ström, annars kunde Aspose.Cells inte få den externa länkens fullständiga sökväg ibland.

### Se även

* class [Workbook](../../workbook)
* namnutrymme [Aspose.Cells](../../workbook)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->