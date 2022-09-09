---
title: SetSeriesNames
second_title: Справочник по Aspose.Cells для .NET API
description: Устанавливает название всех рядов на диаграмме.
type: docs
weight: 110
url: /ru/net/aspose.cells.charts/seriescollection/setseriesnames/
---
## SeriesCollection.SetSeriesNames method

Устанавливает название всех рядов на диаграмме.

```csharp
public void SetSeriesNames(int startIndex, string area, bool isVertical)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | Int32 | Индекс первой серии, которой вы хотите задать имя. |
| area | String | Указывает область для имени серии. |
| isVertical | Boolean | &gt;Указывает, строить ли серию из диапазона значений ячеек по строке или по столбцу. |

### Примечания

Если начальный индекс больше, чем количество серий, он вернется и ничего не сделает.Если заданы данные для смежных ячеек, используйте для их разделения двоеточие. Например, $C$2:$C$5.Если данные задаются в смежных ячейках, используйте запятую для их разделения. Например, ($C$2,$D$5).

### Смотрите также

* class [SeriesCollection](../../seriescollection)
* пространство имен [Aspose.Cells.Charts](../../seriescollection)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->