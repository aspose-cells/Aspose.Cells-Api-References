---
title: UndoManager
second_title: Référence de l'API Aspose.Cells pour .NET
description: Encapsule lobjet qui gère les opérations dannulation/rétablissement.
type: docs
weight: 1030
url: /fr/net/aspose.cells.griddesktop/undomanager/
---
## UndoManager class

Encapsule l'objet qui gère les opérations d'annulation/rétablissement.

```csharp
public class UndoManager
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Enabled](../../aspose.cells.griddesktop/undomanager/enabled) { get; set; } | Obtient ou définit une valeur indiquant si la fonction Annuler est activée. La valeur par défaut est false. |
| [RedoStepsCount](../../aspose.cells.griddesktop/undomanager/redostepscount) { get; } | Obtient le nombre actuel d'étapes de rétablissement disponibles. |
| [UndoStackSize](../../aspose.cells.griddesktop/undomanager/undostacksize) { get; set; } | Obtient ou définit la taille de la pile d'annulation/rétablissement. La valeur par défaut est 300. |
| [UndoStepsCount](../../aspose.cells.griddesktop/undomanager/undostepscount) { get; } | Obtient le nombre actuel d'étapes d'annulation disponibles. |

## Méthodes

| Nom | La description |
| --- | --- |
| [BeginChanges](../../aspose.cells.griddesktop/undomanager/beginchanges)() | Commence à enregistrer les modifications. |
| [BeginMark](../../aspose.cells.griddesktop/undomanager/beginmark)() | Commence à marquer les modifications. |
| [ClearStack](../../aspose.cells.griddesktop/undomanager/clearstack)() | Efface les piles Annuler et Rétablir. |
| [EndChanges](../../aspose.cells.griddesktop/undomanager/endchanges)() | Termine l'enregistrement des modifications. |
| [EndMark](../../aspose.cells.griddesktop/undomanager/endmark)() | Se termine pour marquer les modifications. |
| [Redo](../../aspose.cells.griddesktop/undomanager/redo)() | Effectue une opération de rétablissement. |
| [RedoMark](../../aspose.cells.griddesktop/undomanager/redomark)() | Effectue une opération de rétablissement avec mark. |
| [Undo](../../aspose.cells.griddesktop/undomanager/undo)() | Effectue une opération d'annulation. |
| [UndoMark](../../aspose.cells.griddesktop/undomanager/undomark)() | Effectue une opération d'annulation avec mark. |

### Voir également

* espace de noms [Aspose.Cells.GridDesktop](../../aspose.cells.griddesktop)
* Assemblée [Aspose.Cells.GridDesktop](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->