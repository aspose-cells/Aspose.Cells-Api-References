---
title: ExportDataTable
second_title: Aspose.Cells لمرجع .NET API
description: يتم تصدير البيانات بتنسيقCellsaspose.cells/cells جمع لDataTable الكائن .
type: docs
weight: 610
url: /ar/net/aspose.cells/cells/exportdatatable/
---
## ExportDataTable(int, int, int, int) {#exportdatatable}

يتم تصدير البيانات بتنسيق[`Cells`](../../cells) جمع لDataTable الكائن .

```csharp
public DataTable ExportDataTable(int firstRow, int firstColumn, int totalRows, int totalColumns)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstRow | Int32 | رقم صف الخلية الأولى المطلوب تصديرها. |
| firstColumn | Int32 | رقم العمود الخاص بالخلية الأولى المطلوب تصديرها. |
| totalRows | Int32 | عدد الصفوف المراد استيرادها. |
| totalColumns | Int32 | عدد الأعمدة التي سيتم استيرادها. |

### قيمة الإرجاع

تصديرDataTable هدف.

### ملاحظات

إذا كنت تستخدم هذه الطريقة لتصدير كتلة من البيانات ، فالرجاء التأكد من أن البيانات الموجودة في العمود يجب أن تكون من نفس نوع البيانات. خلاف ذلك ، استخدم ملف[`ExportDataTableAsString`](../exportdatatableasstring)الطريقة بدلاً من ذلك.

### أمثلة

```csharp
[C#]


string designerFile = "List.xls";
Workbook excel = new Workbook(designerFile);
Worksheet sheet = excel.Worksheets[0];
DataTable dt = sheet.Cells.ExportDataTable(6, 1, 69, 4);

[Visual Basic]


Dim designerFile As String = "List.xls"
Dim excel As excel = New excel(designerFile)
Dim sheet As Worksheet = excel.Worksheets(0)
Dim dt As DataTable = sheet.Cells.ExportDataTable(6, 1, 69, 4)
```

### أنظر أيضا

* class [Cells](../../cells)
* مساحة الاسم [Aspose.Cells](../../cells)
* المجسم [Aspose.Cells](../../../)

---

## ExportDataTable(int, int, int, int, bool) {#exportdatatable_2}

يتم تصدير البيانات بتنسيق[`Cells`](../../cells) جمع لDataTable الكائن .

```csharp
public DataTable ExportDataTable(int firstRow, int firstColumn, int totalRows, int totalColumns, 
    bool exportColumnName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstRow | Int32 | رقم صف الخلية الأولى المطلوب تصديرها. |
| firstColumn | Int32 | رقم العمود الخاص بالخلية الأولى المطلوب تصديرها. |
| totalRows | Int32 | عدد الصفوف المراد استيرادها. |
| totalColumns | Int32 | عدد الأعمدة التي سيتم استيرادها. |
| exportColumnName | Boolean | الإشارة إلى ما إذا كان سيتم تصدير البيانات الموجودة في الصف الأول إلى اسم عمود DataTable. |

### قيمة الإرجاع

تصديرDataTable هدف.

### أنظر أيضا

* class [Cells](../../cells)
* مساحة الاسم [Aspose.Cells](../../cells)
* المجسم [Aspose.Cells](../../../)

---

## ExportDataTable(int, int, int, int, ExportTableOptions) {#exportdatatable_1}

يتم تصدير البيانات بتنسيق[`Cells`](../../cells) جمع لDataTable الكائن .

```csharp
public DataTable ExportDataTable(int firstRow, int firstColumn, int totalRows, int totalColumns, 
    ExportTableOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| firstRow | Int32 | رقم صف الخلية الأولى المطلوب تصديرها. |
| firstColumn | Int32 | رقم العمود الخاص بالخلية الأولى المطلوب تصديرها. |
| totalRows | Int32 | عدد الصفوف المراد استيرادها. |
| totalColumns | Int32 | عدد الأعمدة التي سيتم استيرادها. |
| options | ExportTableOptions | جميع خيارات جدول التصدير |

### قيمة الإرجاع

تصديرDataTable هدف.

### أنظر أيضا

* class [ExportTableOptions](../../exporttableoptions)
* class [Cells](../../cells)
* مساحة الاسم [Aspose.Cells](../../cells)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->