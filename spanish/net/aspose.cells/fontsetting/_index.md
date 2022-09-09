---
title: FontSetting
second_title: Referencia de API de Aspose.Cells para .NET
description: Representa un rango de caracteres dentro del texto de la celda.
type: docs
weight: 3520
url: /es/net/aspose.cells/fontsetting/
---
## FontSetting class

Representa un rango de caracteres dentro del texto de la celda.

```csharp
public class FontSetting
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontSetting](fontsetting)(int, int, WorksheetCollection) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Font](../../aspose.cells/fontsetting/font) { get; } | Devuelve la fuente de este objeto. |
| [Length](../../aspose.cells/fontsetting/length) { get; } | Obtiene la longitud de los caracteres. |
| [StartIndex](../../aspose.cells/fontsetting/startindex) { get; } | Obtiene el índice de inicio de los caracteres. |
| [TextOptions](../../aspose.cells/fontsetting/textoptions) { get; } | Devuelve las opciones de texto. |
| virtual [Type](../../aspose.cells/fontsetting/type) { get; } | Obtiene el tipo de nodo de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetWordArtStyle](../../aspose.cells/fontsetting/setwordartstyle)(PresetWordArtStyle) | Establece el estilo predeterminado de WordArt. |

### Ejemplos

```csharp

[C#]

// Instanciando un objeto Workbook
Workbook workbook = new Workbook();

//Agregar una nueva hoja de cálculo al objeto de Excel
workbook.Worksheets.Add();

//Obteniendo la referencia de la hoja de trabajo recién agregada pasando su índice de hoja
Worksheet worksheet = workbook.Worksheets[0];

//Accediendo a la celda "A1" de la hoja de trabajo
Aspose.Cells.Cell cell = worksheet.Cells["A1"];

//Añadiendo algún valor a la celda "A1"
cell.PutValue("Visit Aspose!");

//obteniendo personaje
FontSetting charactor = cell.Characters(6, 7);

//Configurar la fuente de los caracteres seleccionados en negrita
charactor.Font.IsBold = true;

//Establecer el color de fuente de los caracteres seleccionados en azul
charactor.Font.Color = Color.Blue;

//Guardando el archivo de Excel
workbook.Save("book1.xls");

[VB.NET]

'Crear una instancia de un objeto Workbook
Dim workbook As Workbook = New Workbook()

'Agregar una nueva hoja de cálculo al objeto de Excel
workbook.Worksheets.Add()

'Obtener la referencia de la hoja de trabajo recién agregada pasando su índice de hoja
Dim worksheet As Worksheet = workbook.Worksheets(0)

'Accessing the "A1" cell from the worksheet
Dim cell As Aspose.Cells.Cell = worksheet.Cells("A1")

'Adding some value to the "A1" cell
cell.PutValue("Visit Aspose!")

'conseguir personaje
Dim charactor As FontSetting = cell.Characters(6, 7)

'Establecer la fuente de los caracteres seleccionados en negrita
charactor.Font.IsBold = True

'Establecer el color de fuente de los caracteres seleccionados en azul
charactor.Font.Color = Color.Blue

'Guardar el archivo de Excel
workbook.Save("book1.xls")
 
```

### Ver también

* espacio de nombres [Aspose.Cells](../../aspose.cells)
* asamblea [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->