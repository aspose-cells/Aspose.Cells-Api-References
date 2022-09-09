---
title: FinishLoadFile
second_title: Aspose.Cells لمرجع .NET API
description: يحدث عند تحميل المصنف .
type: docs
weight: 550
url: /ar/net/aspose.cells.griddesktop/griddesktop/finishloadfile/
---
## GridDesktop.FinishLoadFile event

يحدث عند تحميل المصنف .

```csharp
public event WorkbookEventHandler FinishLoadFile;
```

### أمثلة

```csharp
[C#]
private void gridDesktop1_FinishLoadFile(object sender, Aspose.Cells.GridDesktop.WorkBookEvents e)
{
	MessageBox.Show("finish load file!");
}

[Visual Basic]
Private  Sub gridDesktop1_FinishLoadFile(ByVal sender As Object, ByVal e As Aspose.Cells.GridDesktop.WorkBookEvents) Handles gridDesktop1.FinishLoadFile
	MessageBox.Show("finish load file!")
End Sub

```

### أنظر أيضا

* delegate [WorkbookEventHandler](../../workbookeventhandler)
* class [GridDesktop](../../griddesktop)
* مساحة الاسم [Aspose.Cells.GridDesktop](../../griddesktop)
* المجسم [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->