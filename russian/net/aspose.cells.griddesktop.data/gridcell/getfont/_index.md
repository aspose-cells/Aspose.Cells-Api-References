---
title: GetFont
second_title: Справочник по Aspose.Cells для .NET API
description: Получает шрифт ячейки. При изменении шрифта вы должны вызвать метод SetFont для установки шрифта ячейки.
type: docs
weight: 250
url: /ru/net/aspose.cells.griddesktop.data/gridcell/getfont/
---
## GridCell.GetFont method

Получает шрифт ячейки. При изменении шрифта вы должны вызвать метод "SetFont", для установки шрифта ячейки.

```csharp
public Font GetFont()
```

### Возвращаемое значение

вернуть копию шрифта ячейки.

### Примеры

```csharp
[C#]
GridCell cell = gridDesktop1.GetActiveWorksheet().Cells[0, 0];
Font font = new Font("Courier New", 8, FontStyle.Italic);
cell.SetFont(font);
Color color = cell.GetFontColor();
color = Color.Black;
cell.SetFontColor(color);

[Visual Basic]
Dim cell As GridCell =  gridDesktop1.GetActiveWorksheet().Cells(0, 0) 
Dim font As Font =  New Font("Courier New",8,FontStyle.Italic) 
cell.SetFont(font)
Dim color As Color =  cell.GetFontColor() 
color = Color.Black
cell.SetFontColor(color)

```

### Смотрите также

* class [GridCell](../../gridcell)
* пространство имен [Aspose.Cells.GridDesktop.Data](../../gridcell)
* сборка [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->