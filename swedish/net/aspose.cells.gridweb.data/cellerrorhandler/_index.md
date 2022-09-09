---
title: CellErrorHandler
second_title: Aspose.Cells för .NET API-referens
description: Representerar gränssnittet som avser att hantera cellfelhändelser.
type: docs
weight: 80
url: /sv/net/aspose.cells.gridweb.data/cellerrorhandler/
---
## CellErrorHandler delegate

Representerar gränssnittet som avser att hantera cellfelhändelser.

tomhet **handleCellEvent**(Objektavsändare, GridCellException ex, OnErrorActionQuery-fråga);

```csharp
public delegate void CellErrorHandler(object sender, WebCellException ex, 
    OnErrorActionQuery action);
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sender | Object | Källan till händelsen. |
| ex | WebCellException | Celloperationsfelet. |
| action | OnErrorActionQuery | kan få information om felåtgärdstyp. |

### Se även

* class [WebCellException](../webcellexception)
* class [OnErrorActionQuery](../onerroractionquery)
* namnutrymme [Aspose.Cells.GridWeb.Data](../../aspose.cells.gridweb.data)
* hopsättning [Aspose.Cells.GridWeb](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->