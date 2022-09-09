---
title: Subtotal
second_title: Справочник по Aspose.Cells для .NET API
description: Создает промежуточные итоги для диапазона.
type: docs
weight: 1310
url: /ru/net/aspose.cells/cells/subtotal/
---
## Subtotal(CellArea, int, ConsolidationFunction, int[]) {#subtotal}

Создает промежуточные итоги для диапазона.

```csharp
public void Subtotal(CellArea ca, int groupBy, ConsolidationFunction function, int[] totalList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ca | CellArea | Диапазон |
| groupBy | Int32 | Поле для группировки в виде целочисленного смещения, отсчитываемого от нуля. |
| function | ConsolidationFunction | Функция промежуточного итога. |
| totalList | Int32[] | Массив отсчитываемых от нуля смещений полей, указывающий поля, к которым добавляются промежуточные итоги. |

### Смотрите также

* struct [CellArea](../../cellarea)
* enum [ConsolidationFunction](../../consolidationfunction)
* class [Cells](../../cells)
* пространство имен [Aspose.Cells](../../cells)
* сборка [Aspose.Cells](../../../)

---

## Subtotal(CellArea, int, ConsolidationFunction, int[], bool, bool, bool) {#subtotal_1}

Создает промежуточные итоги для диапазона.

```csharp
public void Subtotal(CellArea ca, int groupBy, ConsolidationFunction function, int[] totalList, 
    bool replace, bool pageBreaks, bool summaryBelowData)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ca | CellArea | Диапазон |
| groupBy | Int32 | Поле для группировки в виде целочисленного смещения, отсчитываемого от нуля. |
| function | ConsolidationFunction | Функция промежуточного итога. |
| totalList | Int32[] | Массив отсчитываемых от нуля смещений полей, указывающий поля, к которым добавляются промежуточные итоги. |
| replace | Boolean | Указывает, заменять ли текущие промежуточные итоги |
| pageBreaks | Boolean | Указывает, добавлять ли разрыв страницы между группами |
| summaryBelowData | Boolean | Указывает, следует ли добавлять сводку ниже данных. |

### Смотрите также

* struct [CellArea](../../cellarea)
* enum [ConsolidationFunction](../../consolidationfunction)
* class [Cells](../../cells)
* пространство имен [Aspose.Cells](../../cells)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->