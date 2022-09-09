---
title: OriginalWidthCM
second_title: Referencia de API de Aspose.Cells para .NET
description: Obtiene el ancho original de la imagen en unidades de centímetros.
type: docs
weight: 140
url: /es/net/aspose.cells.drawing/picture/originalwidthcm/
---
## Picture.OriginalWidthCM property

Obtiene el ancho original de la imagen, en unidades de centímetros.

```csharp
public double OriginalWidthCM { get; }
```

### Ejemplos

```csharp

[C#]
// Instanciando un objeto Workbook
Workbook workbook = new Workbook();
Worksheet worksheet = workbook.Worksheets[0];
// Agregar una imagen en la ubicación de una celda cuyos índices de fila y columna son 1 en la hoja de trabajo. Es celda "B2"
int imgIndex = worksheet.Pictures.Add(1, 1, "example.jpeg");
//Obtener el objeto de imagen insertado
Picture pic = worksheet.Pictures[imgIndex];
//Obtiene el ancho original de la imagen.
double picWidthCM = pic.OriginalWidthCM;
//Guardar el archivo de Excel.
workbook.Save("result.xlsx");
```

### Ver también

* class [Picture](../../picture)
* espacio de nombres [Aspose.Cells.Drawing](../../picture)
* asamblea [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->