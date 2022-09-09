---
title: AddAreas
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Applica la convalida a determinate aree.
type: docs
weight: 180
url: /it/net/aspose.cells/validation/addareas/
---
## Validation.AddAreas method

Applica la convalida a determinate aree.

```csharp
public void AddAreas(CellArea[] areas, bool checkIntersection, bool checkEdge)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| areas | CellArea[] | Le aree. |
| checkIntersection | Boolean | Se controllare l'intersezione di una determinata area con le aree delle convalide esistenti. Se una convalida è stata applicata in una determinata area (o parte di essa), allora la convalida esistente dovrebbe essere rimossa inizialmente da una determinata area. In caso contrario potrebbe essere causato il danneggiamento per le Convalide generate. Se l'utente è sicuro che tutte le aree aggiunte non si intersecano con nessuna area esistente, questo parametro può essere impostato su false per considerazioni sulle prestazioni. |
| checkEdge | Boolean | Se controllare il bordo delle aree applicate di questa convalida. Le impostazioni interne della convalida dipendono da quello in alto a sinistra dei suoi intervalli applicati, quindi se una di determinate aree diventerà la nuova in alto a sinistra degli intervalli applicati, le impostazioni interne deve essere modificato e ricostruito, altrimenti potrebbero verificarsi risultati imprevisti. Se l'utente è sicuro che nessuna di queste aree aggiunte sia in alto a sinistra, questo parametro può essere impostato su false per considerazioni sulle prestazioni. |

### Osservazioni

In questo metodo, rimuoveremo tutte le vecchie convalide in una determinata area. Per quello in alto a sinistra degli intervalli applicati di Validation, in primo luogo la sua StartRow è la più piccola, in secondo luogo la sua StartColumn è la più piccola di quelle aree che hanno la stessa StartRow più piccola .

### Guarda anche

* struct [CellArea](../../cellarea)
* class [Validation](../../validation)
* spazio dei nomi [Aspose.Cells](../../validation)
* assemblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->