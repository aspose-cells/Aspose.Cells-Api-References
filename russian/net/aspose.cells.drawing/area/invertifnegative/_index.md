---
title: InvertIfNegative
second_title: Справочник по Aspose.Cells для .NET API
description: Если свойство истинно и значение точки диаграммы является отрицательным числом цвет переднего плана и цвет фона будут заменены местами.
type: docs
weight: 50
url: /ru/net/aspose.cells.drawing/area/invertifnegative/
---
## Area.InvertIfNegative property

Если свойство истинно и значение точки диаграммы является отрицательным числом, цвет переднего плана и цвет фона будут заменены местами.

```csharp
public bool InvertIfNegative { get; set; }
```

### Примеры

```csharp

[C#]

//Создание экземпляра объекта Workbook
Workbook workbook = new Workbook();
//Добавление нового рабочего листа в объект Workbook
int sheetIndex = workbook.Worksheets.Add();
//Получение ссылки на недавно добавленный рабочий лист путем передачи его индекса листа
Worksheet worksheet = workbook.Worksheets[sheetIndex];
//Добавление пробного значения в ячейку "A1"
worksheet.Cells["A1"].PutValue(50);
//Добавление образца значения в ячейку "A2"
worksheet.Cells["A2"].PutValue(-100);
//Добавление образца значения в ячейку "A3"
worksheet.Cells["A3"].PutValue(150);
//Добавляем диаграмму на рабочий лист
int chartIndex = worksheet.Charts.Add(ChartType.Column, 5, 0, 15, 5);
//Доступ к экземпляру только что добавленного графика
Chart chart = worksheet.Charts[chartIndex];
//Добавление NSeries (источника данных диаграммы) на диаграмму в диапазоне от ячейки "A1" до "A3"
chart.NSeries.Add("A1:A3", true);
chart.NSeries[0].Area.InvertIfNegative = true;
//Установка цвета переднего плана 1-й области NSeries
chart.NSeries[0].Area.ForegroundColor = Color.Red;
//Установка цвета фона 1-й области NSeries.
// Цвет отображаемой области второй точки графика будет цветом фона.
chart.NSeries[0].Area.BackgroundColor = Color.Yellow;
//Сохранение файла Excel
workbook.Save("book1.xls");

[Visual Basic]

'Создание экземпляра объекта Workbook
Dim workbook As Workbook = New Workbook()
'Добавление нового рабочего листа в объект Workbook
Dim sheetIndex As Integer = workbook.Worksheets.Add()
'Получение ссылки на недавно добавленный рабочий лист путем передачи его индекса листа
Dim worksheet As Worksheet = workbook.Worksheets(sheetIndex)
'Adding a sample value to "A1" cell
worksheet.Cells("A1").PutValue(50)
'Adding a sample value to "A2" cell
worksheet.Cells("A2").PutValue(-100)
'Adding a sample value to "A3" cell
worksheet.Cells("A3").PutValue(150)
'Добавление диаграммы на рабочий лист
Dim chartIndex As Integer = worksheet.Charts.Add(ChartType.Column, 5, 0, 15, 5)
'Доступ к экземпляру вновь добавленной диаграммы
Dim chart As Chart = worksheet.Charts(chartIndex)
'Adding NSeries (chart data source) to the chart ranging from "A1" cell to "A3"
chart.NSeries.Add("A1:A3", True)
chart.NSeries(0).Area.InvertIfNegative = True
'Установка цвета переднего плана 1-й области NSeries
chart.NSeries(0).Area.ForegroundColor = Color.Red
'Установка цвета фона 1-й области NSeries.
'Цвет отображаемой области второй точки графика будет цветом фона.
chart.NSeries(0).Area.BackgroundColor = Color.Yellow
'Сохранение файла Excel
workbook.Save("book1.xls")

```

### Смотрите также

* class [Area](../../area)
* пространство имен [Aspose.Cells.Drawing](../../area)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->