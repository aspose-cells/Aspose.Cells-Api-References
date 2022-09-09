---
title: Floor
second_title: Referencia de API de Aspose.Cells para .NET
description: Encapsula el objeto que representa el suelo de un gráfico 3D.
type: docs
weight: 660
url: /es/net/aspose.cells.charts/floor/
---
## Floor class

Encapsula el objeto que representa el suelo de un gráfico 3D.

```csharp
public class Floor : Area
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.cells.drawing/area/backgroundcolor) { get; set; } | Obtiene o establece el fondoColor del[`Area`](../../aspose.cells.drawing/area) . |
| [Border](../../aspose.cells.charts/floor/border) { get; set; } | Obtiene o establece el borde[`Line`](../../aspose.cells.drawing/line) . |
| [FillFormat](../../aspose.cells.drawing/area/fillformat) { get; } | Representa un objeto que contiene propiedades de formato de relleno para el gráfico o la forma especificados. |
| [ForegroundColor](../../aspose.cells.drawing/area/foregroundcolor) { get; set; } | Obtiene o establece el primer planoColor . |
| [Formatting](../../aspose.cells.drawing/area/formatting) { get; set; } | Representa el formato del área. |
| [InvertIfNegative](../../aspose.cells.drawing/area/invertifnegative) { get; set; } | Si la propiedad es verdadera y el valor del punto del gráfico es un número negativo, se intercambiarán el color frontal y el color de fondo. |
| [Transparency](../../aspose.cells.drawing/area/transparency) { get; set; } | Devuelve o establece el grado de transparencia del área como un valor de 0,0 (opaco) a 1,0 (transparente). |

### Ejemplos

```csharp

[C#]

// Instanciar la clase de Licencia
Aspose.Cells.License license = new Aspose.Cells.License();

//Pase solo el nombre del archivo de licencia incrustado en el ensamblado
license.SetLicense("Aspose.Cells.lic");

//Crear una instancia del objeto del libro de trabajo
Workbook workbook = new Workbook();

//Obtener colección de celdas
Cells cells = workbook.Worksheets[0].Cells;

// Poner valores en las celdas
cells["A1"].PutValue(1);

cells["A2"].PutValue(2);

cells["A3"].PutValue(3);

// obtener la colección de gráficos
ChartCollection charts = workbook.Worksheets[0].Charts;

//añadir un nuevo gráfico 
int index = charts.Add(ChartType.Column3DStacked, 5, 0, 15, 5);

// obtener el gráfico recién agregado
Chart chart = charts[index];

// establecer gráficos nseries
chart.NSeries.Add("A1:A3", true);

//Mostrar etiquetas de datos
chart.NSeries[0].DataLabels.ShowValue = true;

//Obtener el suelo del gráfico
Floor floor = chart.Floor;

//establecer el borde del piso en rojo
floor.Border.Color = System.Drawing.Color.Red;

// establecer formato de relleno
floor.FillFormat.SetPresetColorGradient(GradientPresetType.CalmWater, GradientStyleType.DiagonalDown, 2); 

//guarda el archivo
workbook.Save(@"dest.xls");

[VB.NET]

'Crear una instancia de la clase de licencia
Dim license As New Aspose.Cells.License()

'Pase solo el nombre del archivo de licencia incrustado en el ensamblado
license.SetLicense("Aspose.Cells.lic")

'Crear una instancia del objeto del libro
Dim workbook As Workbook = New Workbook()

'Obtener colección de celdas
Dim cells As Cells = workbook.Worksheets(0).Cells

'Poner valores en celdas
cells("A1").PutValue(1)

cells("A2").PutValue(2)

cells("A3").PutValue(3)

'obtener la colección de gráficos
Dim charts As ChartCollection = workbook.Worksheets(0).Charts

'añadir un nuevo gráfico 
Dim index As Integer = charts.Add(ChartType.Column3DStacked, 5, 0, 15, 5)

'obtener el gráfico recién agregado
Dim chart As Chart = charts(index)

'establecer gráficos nseries
chart.NSeries.Add("A1:A3", True)

'Mostrar etiquetas de datos
chart.NSeries(0).DataLabels.ShowValue = True

'Get chart's floor
Dim floor As Floor = chart.Floor

'set floor's border as red
floor.Border.Color = System.Drawing.Color.Red

'establecer formato de relleno
floor.FillFormat.SetPresetColorGradient(GradientPresetType.CalmWater, GradientStyleType.DiagonalDown, 2)

'guarda el archivo
workbook.Save("dest.xls")

```

### Ver también

* class [Area](../../aspose.cells.drawing/area)
* espacio de nombres [Aspose.Cells.Charts](../../aspose.cells.charts)
* asamblea [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->