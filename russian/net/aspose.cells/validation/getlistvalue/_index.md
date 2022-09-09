---
title: GetListValue
second_title: Справочник по Aspose.Cells для .NET API
description: Получить значение списка проверки для указанной ячейки.
type: docs
weight: 220
url: /ru/net/aspose.cells/validation/getlistvalue/
---
## Validation.GetListValue method

Получить значение списка проверки для указанной ячейки.

```csharp
public object GetListValue(int row, int column)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| row | Int32 | Индекс строки. |
| column | Int32 | Индекс столбца. |

### Возвращаемое значение

Значение для создания списка этой проверки для указанной ячейки. Если список ссылается на диапазон, то возвращаемое значение будет[`ReferredArea`](../../referredarea) объект; В противном случае возвращаемое значение может быть нулевым, объектом[] или простым объектом.

### Примечания

Только для проверки, тип которой — список и которая была применена к данной ячейке, , в противном случае будет возвращено значение null.

### Смотрите также

* class [Validation](../../validation)
* пространство имен [Aspose.Cells](../../validation)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->