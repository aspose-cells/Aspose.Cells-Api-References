---
title: BeforeLoadFile
second_title: Référence de l'API Aspose.Cells pour .NET
description: Se produit avant le chargement du classeur à partir du fichier.
type: docs
weight: 380
url: /fr/net/aspose.cells.griddesktop/griddesktop/beforeloadfile/
---
## GridDesktop.BeforeLoadFile event

Se produit avant le chargement du classeur à partir du fichier.

```csharp
public event WorkbookEventHandler BeforeLoadFile;
```

### Exemples

```csharp
[C#]
private void gridDesktop1_BeforeLoadFile(object sender, Aspose.Cells.GridDesktop.Event.WorkBookEvents e)
{
	MessageBox.Show("before load file!");
}

[Visual Basic]
Private  Sub gridDesktop1_BeforeLoadFile(ByVal sender As Object, ByVal e As Aspose.Cells.GridDesktop.Event.WorkBookEvents) Handles gridDesktop1.CellDataChanged
	MessageBox.Show("before load file!")
End Sub

```

### Voir également

* delegate [WorkbookEventHandler](../../workbookeventhandler)
* class [GridDesktop](../../griddesktop)
* espace de noms [Aspose.Cells.GridDesktop](../../griddesktop)
* Assemblée [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->