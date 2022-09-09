---
title: AddAutoShape
second_title: Справочник по Aspose.Cells для .NET API
description: Добавляет автофигуру на лист.
type: docs
weight: 40
url: /ru/net/aspose.cells.drawing/shapecollection/addautoshape/
---
## ShapeCollection.AddAutoShape method

Добавляет автофигуру на лист.

```csharp
public Shape AddAutoShape(AutoShapeType type, int upperLeftRow, int top, int upperLeftColumn, 
    int left, int height, int width)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | AutoShapeType | Автоматический тип формы. |
| upperLeftRow | Int32 | Индекс верхней левой строки. |
| top | Int32 | Представляет вертикальное смещение Shape от его левой строки в единицах пикселя. |
| upperLeftColumn | Int32 | Индекс левого верхнего столбца. |
| left | Int32 | Представляет горизонтальное смещение Shape от его левого столбца в пикселях. |
| height | Int32 | Представляет высоту объекта Shape в пикселях. |
| width | Int32 | Представляет ширину Shape в пикселях. |

### Возвращаемое значение

Объект формы.

### Примечания

Тип не может быть Chart/Comment/Picture/OleObject/Polygon/DialogBox.

### Примеры

```csharp

[C#]
//Добавляет автофигуру на лист.
Shape autoShape = shapes.AddAutoShape(AutoShapeType.Cube, 1, 0, 1, 0, 100, 50);
```

### Смотрите также

* class [Shape](../../shape)
* enum [AutoShapeType](../../autoshapetype)
* class [ShapeCollection](../../shapecollection)
* пространство имен [Aspose.Cells.Drawing](../../shapecollection)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->