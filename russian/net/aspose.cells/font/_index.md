---
title: Font
second_title: Справочник по Aspose.Cells для .NET API
description: Инкапсулирует объект шрифта используемый в электронной таблице.
type: docs
weight: 3490
url: /ru/net/aspose.cells/font/
---
## Font class

Инкапсулирует объект шрифта, используемый в электронной таблице.

```csharp
public class Font
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ArgbColor](../../aspose.cells/font/argbcolor) { get; set; } | Получает и устанавливает цвет с 32-битным значением ARGB. |
| [CapsType](../../aspose.cells/font/capstype) { get; set; } | Получает и устанавливает тип прописных букв. |
| [Charset](../../aspose.cells/font/charset) { get; set; } | Представляет набор символов. |
| [Color](../../aspose.cells/font/color) { get; set; } | Получает или задаетColor шрифта. |
| [DoubleSize](../../aspose.cells/font/doublesize) { get; set; } | Получает и устанавливает двойной размер шрифта. |
| [IsBold](../../aspose.cells/font/isbold) { get; set; } | Получает или задает значение, указывающее, является ли шрифт полужирным. |
| [IsItalic](../../aspose.cells/font/isitalic) { get; set; } | Получает или задает значение, указывающее, является ли шрифт курсивным. |
| [IsNormalizeHeights](../../aspose.cells/font/isnormalizeheights) { get; set; } | Указывает, применяется ли нормализация высоты к тексту. |
| [IsStrikeout](../../aspose.cells/font/isstrikeout) { get; set; } | Получает или задает значение, указывающее, является ли шрифт одинарным перечеркнутым. |
| [IsSubscript](../../aspose.cells/font/issubscript) { get; set; } | Получает или задает значение, указывающее, является ли шрифт подстрочным. |
| [IsSuperscript](../../aspose.cells/font/issuperscript) { get; set; } | Получает или задает значение, указывающее, является ли шрифт суперсценарным. |
| virtual [Name](../../aspose.cells/font/name) { get; set; } | Получает или задает имя[`Font`](../font) . |
| [SchemeType](../../aspose.cells/font/schemetype) { get; set; } | Получает и устанавливает тип схемы шрифта. |
| [ScriptOffset](../../aspose.cells/font/scriptoffset) { get; set; } | Получает и задает смещение скрипта в процентах |
| [Size](../../aspose.cells/font/size) { get; set; } | Получает или задает размер шрифта. |
| [StrikeType](../../aspose.cells/font/striketype) { get; set; } | Получает тип удара текста. |
| [ThemeColor](../../aspose.cells/font/themecolor) { get; set; } | Получает и устанавливает цвет темы. |
| [Underline](../../aspose.cells/font/underline) { get; set; } | Получает или задает тип подчеркивания шрифта. |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../aspose.cells/font/equals#equals)(Font) | Проверяет, равны ли два шрифта. |
| override [ToString](../../aspose.cells/font/tostring)() | Возвращает строку, представляющую текущий объект Cell. |

### Примеры

```csharp

[C#]

//Создание экземпляра объекта Workbook
Workbook workbook = new Workbook();

//Получение ссылки на недавно добавленный рабочий лист путем передачи его индекса листа
Worksheet worksheet = workbook.Worksheets[0];

//Доступ к ячейке "A1" из рабочего листа
Aspose.Cells.Cell cell = worksheet.Cells["A1"];

//Добавление некоторого значения в ячейку "A1"
cell.PutValue("Hello Aspose!");

Aspose.Cells.Font font = cell.GetStyle().Font;

//Установка имени шрифта на "Times New Roman"
font.Name = "Times New Roman";

//Установка размера шрифта на 14
font.Size = 14;

//устанавливаем красный цвет шрифта
font.Color = System.Drawing.Color.Red;           

//Сохранение файла Excel
workbook.Save(@"dest.xls");

[VB.NET]

'Создание экземпляра объекта Workbook
Dim workbook As Workbook = New Workbook()

'Получение ссылки на недавно добавленный рабочий лист путем передачи его индекса листа
Dim worksheet As Worksheet = workbook.Worksheets(0)

'Accessing the "A1" cell from the worksheet
Dim cell As Aspose.Cells.Cell = worksheet.Cells("A1")

'Adding some value to the "A1" cell
cell.PutValue("Hello Aspose!")

Dim font As Aspose.Cells.Font = cell.GetStyle().Font

'Setting the font name to "Times New Roman"
font.Name = "Times New Roman"

'Установка размера шрифта на 14
font.Size = 14

'установка цвета шрифта как красный
font.Color = System.Drawing.Color.Red

'Сохранение файла Excel
workbook.Save("dest.xls")
```

### Смотрите также

* пространство имен [Aspose.Cells](../../aspose.cells)
* сборка [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->