---
title: Add
second_title: Aspose.Cells لمرجع .NET API
description: يضيف تعليقًا إلى المجموعة .
type: docs
weight: 20
url: /ar/net/aspose.cells/commentcollection/add/
---
## Add(int, int) {#add}

يضيف تعليقًا إلى المجموعة .

```csharp
public int Add(int row, int column)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| row | Int32 | فهرس صف الخلية. |
| column | Int32 | فهرس عمود الخلية. |

### قيمة الإرجاع

[`Comment`](../../comment) فهرس الكائن.

### أمثلة

```csharp

[C#]
int commentIndex1 = comments.Add(0, 0);
Comment comment1 = comments[commentIndex1];
comment1.Note = "First note.";
comment1.Font.Name = "Times New Roman";
```

### أنظر أيضا

* class [CommentCollection](../../commentcollection)
* مساحة الاسم [Aspose.Cells](../../commentcollection)
* المجسم [Aspose.Cells](../../../)

---

## Add(string) {#add_1}

يضيف تعليقًا إلى المجموعة .

```csharp
public int Add(string cellName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cellName | String | اسم الخلية. |

### قيمة الإرجاع

[`Comment`](../../comment) فهرس الكائن.

### أمثلة

```csharp

[C#]
int commentIndex2 = comments.Add("B2");
Comment comment2 = comments[commentIndex2];
comment2.Note = "Second note.";
comment2.Font.Name = "Times New Roman";
```

### أنظر أيضا

* class [CommentCollection](../../commentcollection)
* مساحة الاسم [Aspose.Cells](../../commentcollection)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->