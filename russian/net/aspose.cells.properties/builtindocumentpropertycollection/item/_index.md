---
title: Item
second_title: Справочник по Aspose.Cells для .NET API
description: ВозвращаетDocumentPropertyaspose.cells.properties/documentproperty объект по имени свойства.
type: docs
weight: 110
url: /ru/net/aspose.cells.properties/builtindocumentpropertycollection/item/
---
## BuiltInDocumentPropertyCollection indexer

Возвращает[`DocumentProperty`](../../documentproperty) объект по имени свойства.

```csharp
public override DocumentProperty this[string name] { get; }
```

| Параметр | Описание |
| --- | --- |
| name | Нечувствительное к регистру имя извлекаемого свойства. |

### Примечания

Строковые имена свойств соответствуют именам свойств typed , доступных из[`BuiltInDocumentPropertyCollection`](../../builtindocumentpropertycollection).

Если вы запрашиваете свойство, которого нет в документе, но свойство name распознается как допустимое встроенное имя, новое[`DocumentProperty`](../../documentproperty) создается, добавляется в коллекцию и возвращается. Вновь созданному свойству присваивается значение по умолчанию (пустая строка, ноль, false или DateTime.MinValue в зависимости от type встроенного свойства).

Если вы запрашиваете свойство, которого нет в документе, а name не распознается как встроенное имя, возвращается null.

### Смотрите также

* class [DocumentProperty](../../documentproperty)
* class [BuiltInDocumentPropertyCollection](../../builtindocumentpropertycollection)
* пространство имен [Aspose.Cells.Properties](../../builtindocumentpropertycollection)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->