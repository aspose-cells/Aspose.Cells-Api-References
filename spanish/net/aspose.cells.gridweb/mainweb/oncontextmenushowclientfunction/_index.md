---
title: OnContextMenuShowClientFunction
second_title: Referencia de API de Aspose.Cells para .NET
description: Obtiene o establece la función del lado del cliente que se llamará cuando se muestre el menú contextual. La función del cliente debe declararse así función enContextMenuShow  var menú  evento.srcElement menu.setItemVisibilityBorrar bloquear menu.setItemVisibilityActualizar ninguno  Nota puede usar el puntero este en la función del cliente para señalar el control de cuadrícula que activa el evento.
type: docs
weight: 620
url: /es/net/aspose.cells.gridweb/mainweb/oncontextmenushowclientfunction/
---
## MainWeb.OnContextMenuShowClientFunction property

Obtiene o establece la función del lado del cliente que se llamará cuando se muestre el menú contextual. La función del cliente debe declararse así: función enContextMenuShow() { var menú = evento.srcElement; menu.setItemVisibility("Borrar", "bloquear"); menu.setItemVisibility("Actualizar", "ninguno"); } Nota: puede usar el puntero "este" en la función del cliente para señalar el control de cuadrícula que activa el evento.

```csharp
public string OnContextMenuShowClientFunction { get; set; }
```

### Ver también

* class [MainWeb](../../mainweb)
* espacio de nombres [Aspose.Cells.GridWeb](../../mainweb)
* asamblea [Aspose.Cells.GridWeb](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->