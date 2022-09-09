---
title: BeforeCalculate
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Si verifica prima del calcolo della formula nella cartella di lavoro.
type: docs
weight: 370
url: /it/net/aspose.cells.griddesktop/griddesktop/beforecalculate/
---
## GridDesktop.BeforeCalculate event

Si verifica prima del calcolo della formula nella cartella di lavoro.

```csharp
public event WorkbookEventHandler BeforeCalculate;
```

### Esempi

```csharp
[C#]
private void gridDesktop1_BeforeCalculate(object sender, Aspose.Cells.GridDesktop.Event.WorkBookEvents e)
{
	MessageBox.Show("before calculate formula!");
}

[Visual Basic]
Private  Sub gridDesktop1_BeforeCalculate(ByVal sender As Object, ByVal e As Aspose.Cells.GridDesktop.Event.WorkBookEvents) Handles gridDesktop1.CellDataChanged
	MessageBox.Show("before calculate formula!")
End Sub

```

### Guarda anche

* delegate [WorkbookEventHandler](../../workbookeventhandler)
* class [GridDesktop](../../griddesktop)
* spazio dei nomi [Aspose.Cells.GridDesktop](../../griddesktop)
* assemblea [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->