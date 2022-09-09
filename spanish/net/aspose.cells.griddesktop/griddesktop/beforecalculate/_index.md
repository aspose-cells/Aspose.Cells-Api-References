---
title: BeforeCalculate
second_title: Referencia de API de Aspose.Cells para .NET
description: Ocurre antes de calcular la fórmula en el libro de trabajo.
type: docs
weight: 370
url: /es/net/aspose.cells.griddesktop/griddesktop/beforecalculate/
---
## GridDesktop.BeforeCalculate event

Ocurre antes de calcular la fórmula en el libro de trabajo.

```csharp
public event WorkbookEventHandler BeforeCalculate;
```

### Ejemplos

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

### Ver también

* delegate [WorkbookEventHandler](../../workbookeventhandler)
* class [GridDesktop](../../griddesktop)
* espacio de nombres [Aspose.Cells.GridDesktop](../../griddesktop)
* asamblea [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->