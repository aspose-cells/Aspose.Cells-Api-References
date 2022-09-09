---
title: AddArea
second_title: Справочник по Aspose.Cells для .NET API
description: Применяет проверку к области.
type: docs
weight: 170
url: /ru/net/aspose.cells/validation/addarea/
---
## AddArea(CellArea) {#addarea}

Применяет проверку к области.

```csharp
public void AddArea(CellArea cellArea)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cellArea | CellArea | Площадь. |

### Примечания

Эквивалентно использованию[`AddArea`](../addarea) с проверкой пересечения и ребра.

### Смотрите также

* struct [CellArea](../../cellarea)
* class [Validation](../../validation)
* пространство имен [Aspose.Cells](../../validation)
* сборка [Aspose.Cells](../../../)

---

## AddArea(CellArea, bool, bool) {#addarea_1}

Применяет проверку к области.

```csharp
public void AddArea(CellArea cellArea, bool checkIntersection, bool checkEdge)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cellArea | CellArea | Площадь. |
| checkIntersection | Boolean | Проверять пересечение данной области с существующими областями валидации. Если одна валидация была применена в данной области (или ее части), , то существующая валидация должна быть сначала удалена из данной области. В противном случае может быть вызвано повреждение для сгенерированных Validations. Если пользователь уверен, что добавленная область не пересекается ни с одной существующей областью, для этого параметра можно установить значение false из соображений производительности. |
| checkEdge | Boolean | Проверять ли край применяемых областей этой проверки. Внутренние настройки проверки зависят от верхнего левого одного из применяемых диапазонов, , поэтому, если данная область станет новым верхним левым одним из примененных диапазонов, , внутренние настройки должны быть изменены и перестроены, в противном случае может быть вызван неожиданный результат. Если пользователь уверен, что добавленная область не является верхней левой, этот параметр может быть установлен как false для соображений производительности. |

### Примечания

В этом методе мы удалим все старые проверки в данной области. Для верхнего левого из примененных диапазонов проверки, во-первых, его StartRow наименьший, во-вторых, его StartColumn является наименьшим из тех областей, которые имеют такой же самый наименьший StartRow .

### Смотрите также

* struct [CellArea](../../cellarea)
* class [Validation](../../validation)
* пространство имен [Aspose.Cells](../../validation)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->