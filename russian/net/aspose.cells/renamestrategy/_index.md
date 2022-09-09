---
title: RenameStrategy
second_title: Справочник по Aspose.Cells для .NET API
description: Вариант стратегии для повторяющихся имен столбцов.
type: docs
weight: 5070
url: /ru/net/aspose.cells/renamestrategy/
---
## RenameStrategy enumeration

Вариант стратегии для повторяющихся имен столбцов.

```csharp
public enum RenameStrategy
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Exception | `0` | Выдает исключение. |
| Digit | `1` | Имя с цифрой. Повторяющиеся имена станут ...1, ...2 и т. д. |
| Letter | `2` | Имя с буквой.. Повторяющиеся имена станут ...A, ...B и т. д. |

### Примечания

При обработке данных с заголовками в некоторых сценариях требуется, чтобы заголовки не дублировались для всех столбцов. Например, при экспорте данных в таблицу данных и требуется, чтобы заголовок использовался как имя столбца таблицы данных, повторяющиеся значения заголовка недействительны. . Для таких ситуаций пользователь может определить, как с ними справиться, указав эту стратегию.

### Смотрите также

* пространство имен [Aspose.Cells](../../aspose.cells)
* сборка [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->