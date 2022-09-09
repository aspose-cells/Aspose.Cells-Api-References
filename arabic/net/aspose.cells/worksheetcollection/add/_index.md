---
title: Add
second_title: Aspose.Cells لمرجع .NET API
description: يضيف ورقة عمل إلى المجموعة.
type: docs
weight: 170
url: /ar/net/aspose.cells/worksheetcollection/add/
---
## Add(SheetType) {#add_2}

يضيف ورقة عمل إلى المجموعة.

```csharp
public int Add(SheetType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| type | SheetType | نوع ورقة العمل. |

### قيمة الإرجاع

[`Worksheet`](../../worksheet) فهرس الكائن.

### أمثلة

```csharp
[C#]
Workbook workbook = new Workbook();
workbook.Worksheets.Add(SheetType.Chart);
Cells cells = workbook.Worksheets[0].Cells;
cells["c2"].PutValue(5000);
cells["c3"].PutValue(3000);
cells["c4"].PutValue(4000);
cells["c5"].PutValue(5000);
cells["c6"].PutValue(6000);
ChartCollection charts = workbook.Worksheets[1].Charts;
int chartIndex = charts.Add(ChartType.Column, 10,10,20,20);
Chart chart = charts[chartIndex];
chart.NSeries.Add("Sheet1!C2:C6", true);

[Visual Basic]
Dim workbook As Workbook =  New Workbook() 
workbook.Worksheets.Add(SheetType.Chart)
Dim cells As Cells = workbook.Worksheets(0).Cells 
cells("c2").PutValue(5000)
cells("c3").PutValue(3000)
cells("c4").PutValue(4000)
cells("c5").PutValue(5000)
cells("c6").PutValue(6000)
Dim charts As ChartCollection = workbook.Worksheets(1).Charts
Dim chartIndex As Integer = charts.Add(ChartType.Column,10,10,20,20) 
Dim chart As Chart = charts(chartIndex) 
chart.NSeries.Add("Sheet1!C2:C6", True)
```

### أنظر أيضا

* enum [SheetType](../../sheettype)
* class [WorksheetCollection](../../worksheetcollection)
* مساحة الاسم [Aspose.Cells](../../worksheetcollection)
* المجسم [Aspose.Cells](../../../)

---

## Add() {#add_1}

يضيف ورقة عمل إلى المجموعة.

```csharp
public int Add()
```

### قيمة الإرجاع

[`Worksheet`](../../worksheet) فهرس الكائن.

### أنظر أيضا

* class [WorksheetCollection](../../worksheetcollection)
* مساحة الاسم [Aspose.Cells](../../worksheetcollection)
* المجسم [Aspose.Cells](../../../)

---

## Add(string) {#add}

يضيف ورقة عمل إلى المجموعة.

```csharp
public Worksheet Add(string sheetName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sheetName | String | اسم ورقة العمل |

### قيمة الإرجاع

[`Worksheet`](../../worksheet) هدف.

### أنظر أيضا

* class [Worksheet](../../worksheet)
* class [WorksheetCollection](../../worksheetcollection)
* مساحة الاسم [Aspose.Cells](../../worksheetcollection)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->