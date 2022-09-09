---
title: Ungroup
second_title: Справочник по Aspose.Cells для .NET API
description: Разгруппирует элементы формы.
type: docs
weight: 440
url: /ru/net/aspose.cells.drawing/shapecollection/ungroup/
---
## ShapeCollection.Ungroup method

Разгруппирует элементы формы.

```csharp
public void Ungroup(GroupShape group)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| group | GroupShape | Форма группы. |

### Примечания

Если фигура группы сгруппирована другой фигурой группы, ничего не будет сделано.

### Примеры

```csharp

[C#]
//добавляем первую фигуру
shapes.AddRectangle(2, 0, 2, 0, 50, 50);
//добавляем вторую фигуру
shapes.AddRectangle(6, 0, 2, 0, 30, 30);

//группа
Shape[] shapesArr = new Shape[] { shapes[0], shapes[1] };
GroupShape groupShape = shapes.Group(shapesArr);

// разгруппировать
shapes.Ungroup(groupShape);

```

### Смотрите также

* class [GroupShape](../../groupshape)
* class [ShapeCollection](../../shapecollection)
* пространство имен [Aspose.Cells.Drawing](../../shapecollection)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->