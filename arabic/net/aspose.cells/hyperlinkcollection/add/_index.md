---
title: Add
second_title: Aspose.Cells لمرجع .NET API
description: إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.
type: docs
weight: 20
url: /ar/net/aspose.cells/hyperlinkcollection/add/
---
## Add(int, int, int, int, string) {#add}

إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.

```csharp
public int Add(int firstRow, int firstColumn, int totalRows, int totalColumns, string address)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstRow | Int32 | الصف الأول من نطاق الارتباط التشعبي. |
| firstColumn | Int32 | العمود الأول لنطاق الارتباط التشعبي. |
| totalRows | Int32 | عدد الصفوف في نطاق الارتباط التشعبي هذا. |
| totalColumns | Int32 | عدد الأعمدة في نطاق الارتباط التشعبي هذا. |
| address | String | عنوان الارتباط التشعبي. |

### قيمة الإرجاع

[`Hyperlink`](../../hyperlink) فهرس الكائن.

### أمثلة

```csharp
[C#]
// إنشاء كائن مصنف
Workbook excel = new Workbook();
Worksheet worksheet = excel.Worksheets[0];
worksheet.Hyperlinks.Add("A4", 1, 1, "http://www.aspose.com ") ;
worksheet.Hyperlinks.Add("A5", 1, 1, "c:\\book1.xls");

[Visual Basic]

'إنشاء كائن مصنف
Dim excel As Workbook = New Workbook()
Dim worksheet as Worksheet = excel.Worksheets(0)
worksheet.Hyperlinks.Add("A4", 1, 1, "http://www.aspose.com ")
worksheet.Hyperlinks.Add("A5", 1, 1, "c:\\book1.xls")

```

### أنظر أيضا

* class [HyperlinkCollection](../../hyperlinkcollection)
* مساحة الاسم [Aspose.Cells](../../hyperlinkcollection)
* المجسم [Aspose.Cells](../../../)

---

## Add(string, int, int, string) {#add_1}

إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.

```csharp
public int Add(string cellName, int totalRows, int totalColumns, string address)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cellName | String | اسم الخلية. |
| totalRows | Int32 | عدد الصفوف في نطاق الارتباط التشعبي هذا. |
| totalColumns | Int32 | عدد الأعمدة في نطاق الارتباط التشعبي هذا. |
| address | String | عنوان الارتباط التشعبي. |

### قيمة الإرجاع

[`Hyperlink`](../../hyperlink) فهرس الكائن.

### أنظر أيضا

* class [HyperlinkCollection](../../hyperlinkcollection)
* مساحة الاسم [Aspose.Cells](../../hyperlinkcollection)
* المجسم [Aspose.Cells](../../../)

---

## Add(string, string, string, string, string) {#add_2}

إضافة ارتباط تشعبي إلى خلية محددة أو نطاق من الخلايا.

```csharp
public int Add(string startCellName, string endCellName, string address, string textToDisplay, 
    string screenTip)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| startCellName | String | الخلية العلوية اليسرى من النطاق. |
| endCellName | String | الخلية اليمنى السفلية من النطاق. |
| address | String | عنوان الارتباط التشعبي. |
| textToDisplay | String | النص الذي سيتم عرضه للارتباط التشعبي المحدد. |
| screenTip | String | نص تلميح الشاشة للارتباط التشعبي المحدد. |

### قيمة الإرجاع

[`Hyperlink`](../../hyperlink) فهرس الكائن.

### أنظر أيضا

* class [HyperlinkCollection](../../hyperlinkcollection)
* مساحة الاسم [Aspose.Cells](../../hyperlinkcollection)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->