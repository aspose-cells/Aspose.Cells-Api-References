---
title: BeforeCalculate
second_title: Aspose.Cells لمرجع .NET API
description: يحدث قبل حساب الصيغة في المصنف.
type: docs
weight: 370
url: /ar/net/aspose.cells.griddesktop/griddesktop/beforecalculate/
---
## GridDesktop.BeforeCalculate event

يحدث قبل حساب الصيغة في المصنف.

```csharp
public event WorkbookEventHandler BeforeCalculate;
```

### أمثلة

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

### أنظر أيضا

* delegate [WorkbookEventHandler](../../workbookeventhandler)
* class [GridDesktop](../../griddesktop)
* مساحة الاسم [Aspose.Cells.GridDesktop](../../griddesktop)
* المجسم [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->