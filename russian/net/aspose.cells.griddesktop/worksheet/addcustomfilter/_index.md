---
title: AddCustomFilter
second_title: Справочник по Aspose.Cells для .NET API
description: Добавить пользовательский фильтр для указанного диапазона строк от начальной до конечной строки.
type: docs
weight: 450
url: /ru/net/aspose.cells.griddesktop/worksheet/addcustomfilter/
---
## AddCustomFilter(int, int, object[], GridFilterOperatorType[]) {#addcustomfilter}

Добавить пользовательский фильтр для указанного диапазона строк от начальной до конечной строки.

```csharp
public void AddCustomFilter(int startrow, int startcolumn, object[] critiras, 
    GridFilterOperatorType[] filterOperatorTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startrow | Int32 | Начальный ряд фильтров |
| startcolumn | Int32 | Начальный столбец диапазона фильтра |
| critiras | Object[] | Массив критических данных для столбцов, каждый из которых применяется к каждому столбцу. |
| filterOperatorTypes | GridFilterOperatorType[] | Массив типов операций фильтра для столбцов, каждый из которых применяется к каждому столбцу |

### Смотрите также

* enum [GridFilterOperatorType](../../../aspose.cells.griddesktop.data/gridfilteroperatortype)
* class [Worksheet](../../worksheet)
* пространство имен [Aspose.Cells.GridDesktop](../../worksheet)
* сборка [Aspose.Cells.GridDesktop](../../../)

---

## AddCustomFilter(int, string) {#addcustomfilter_1}

Добавить пользовательский фильтр для указанной строки.

```csharp
public void AddCustomFilter(int row, string critira)
```

### Примечания

Строка критериев фильтра. обратите внимание мы используем , и ; как разделенный символ, поэтому значение ячейки не должно содержать эти разделенные char , ниже приведены примеры строк критериев: // столбец 0 со значением 12.3 CELL0 = 12.3 // столбец 1 со значением ABC CELL1 = ABC // столбец 0 со значением значение 123 или 456 или ABC и столбец 1 со значением ABC CELL0 = 123 456,ABC; ЯЧЕЙКА1 = ABC

### Смотрите также

* class [Worksheet](../../worksheet)
* пространство имен [Aspose.Cells.GridDesktop](../../worksheet)
* сборка [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->