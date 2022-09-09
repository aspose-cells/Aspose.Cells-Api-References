---
title: GridTableItemStyle
second_title: Aspose.Cells لمرجع .NET API
description: موروث من System.Web.UI.WebControls.TableItemStyle. يغلف أنماط WebCell.
type: docs
weight: 780
url: /ar/net/aspose.cells.gridweb/gridtableitemstyle/
---
## GridTableItemStyle class

موروث من System.Web.UI.WebControls.TableItemStyle. يغلف أنماط WebCell.

```csharp
public class GridTableItemStyle : TableItemStyle
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GridTableItemStyle](gridtableitemstyle)() | المُنشئ الافتراضي . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BackImageAttributes](../../aspose.cells.gridweb/gridtableitemstyle/backimageattributes) { get; set; } | سمات صورة الخلفية . |
| [BackImageUrl](../../aspose.cells.gridweb/gridtableitemstyle/backimageurl) { get; set; } | عنوان url لصورة الخلفية . |
| [BottomBorderStyle](../../aspose.cells.gridweb/gridtableitemstyle/bottomborderstyle) { get; set; } | يحدد نمط الحد السفلي للخلية. |
| [Custom](../../aspose.cells.gridweb/gridtableitemstyle/custom) { get; set; } | الحصول على التنسيق المخصص أو تعيينه ، فالسلسلة الفارغة أو الفارغة تعني عدم وجود تنسيق مخصص. |
| [IndentLevel](../../aspose.cells.gridweb/gridtableitemstyle/indentlevel) { get; set; } | الحصول على أو تعيين مستوى المسافة البادئة . |
| [IsLocked](../../aspose.cells.gridweb/gridtableitemstyle/islocked) { get; set; } | الحصول على قيمة أو تعيينها تشير إلى إمكانية تعديل الخلية أم لا عندما تكون ورقة العمل محمية . عندما تكون ورقة العمل محمية ويكون IsLocked صحيحًا ، لا يمكن تحرير الخلية. عندما تكون ورقة العمل الخاصة بها محمية بـ وتكون IsLocked خاطئة ، يمكن تحرير الخلية. |
| [LeftBorderStyle](../../aspose.cells.gridweb/gridtableitemstyle/leftborderstyle) { get; set; } | يحدد نمط الحد الأيسر للخلية. |
| [NumberType](../../aspose.cells.gridweb/gridtableitemstyle/numbertype) { get; set; } | الحصول على تنسيق عرض الأرقام والتواريخ أو تحديده. |
| [RightBorderStyle](../../aspose.cells.gridweb/gridtableitemstyle/rightborderstyle) { get; set; } | يحدد نمط الحد الأيمن للخلية. |
| [RotationAngle](../../aspose.cells.gridweb/gridtableitemstyle/rotationangle) { get; set; } | الحصول على أو تعيين سمة التدوير . |
| [TopBorderStyle](../../aspose.cells.gridweb/gridtableitemstyle/topborderstyle) { get; set; } | يحدد نمط الحد العلوي للخلية. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [AddAttributesToRender](../../aspose.cells.gridweb/gridtableitemstyle/addattributestorender#addattributestorender_1)(HtmlTextWriter, WebControl) | الاستخدام الداخلي فقط. طريقة التنفيذ لا تقم باستدعاء هذه الطريقة مباشرة. |
| override [CopyFrom](../../aspose.cells.gridweb/gridtableitemstyle/copyfrom)(Style) | نُسخ من كائن نمط آخر . |
| override [GetHashCode](../../aspose.cells.gridweb/gridtableitemstyle/gethashcode)() | تعمل كدالة تجزئة لنوع معين ، ومناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| override [MergeWith](../../aspose.cells.gridweb/gridtableitemstyle/mergewith)(Style) | يدمج مع كائن نمط آخر. |

### أمثلة

```csharp
[C#]
...
using System.Web.UI.WebControls;
...
...
WebWorksheets sheets = GridWeb1.WebWorksheets;
sheets.Clear();
WebWorksheet sheet = sheets[sheets.Add("demo1")];

WebCell cell = sheet.Cells[0,0];
cell.StringValue = "Demo Text";

Aspose.Cells.GridWeb.TableItemStyle style = cell.GetStyle();
style.Font.Size = new FontUnit("72pt");
style.Wrap = false;

style.BackColor = Color.Gray;
style.BorderStyle = BorderStyle.Solid;
style.BorderWidth = new Unit(1, UnitType.Pixel);
style.BorderColor = Color.Silver;

style.RightBorderStyle.BorderColor = Color.Black;
style.RightBorderStyle.BorderStyle = BorderStyle.Solid;
style.RightBorderStyle.BorderWidth = new Unit(1, UnitType.Pixel);
style.BottomBorderStyle.BorderColor = Color.Black;
style.BottomBorderStyle.BorderStyle = BorderStyle.Solid;
style.BottomBorderStyle.BorderWidth = new Unit(1, UnitType.Pixel);
cell.SetStyle(style);

[Visual Basic]
...
Imports System.Web.UI.WebControls
...
...
Dim sheets As WebWorksheets =  GridWeb1.WebWorksheets
sheets.Clear()
Dim sheet As WebWorksheet =  sheets(sheets.Add(__0__))

Dim cell As WebCell =  sheet.Cells(0,0)
cell.StringValue = "Demo Text"

Dim style As Aspose.Cells.GridWeb.TableItemStyle = cell.GetStyle()
style.Font.Size = New FontUnit("72pt")
style.Wrap = False

style.BackColor = Color.Gray
style.BorderStyle = BorderStyle.Solid
style.BorderWidth = New Unit(1, UnitType.Pixel)
style.BorderColor = Color.Silver

style.RightBorderStyle.BorderColor = Color.Black
style.RightBorderStyle.BorderStyle = BorderStyle.Solid
style.RightBorderStyle.BorderWidth = New Unit(1, UnitType.Pixel)
style.BottomBorderStyle.BorderColor = Color.Black
style.BottomBorderStyle.BorderStyle = BorderStyle.Solid
style.BottomBorderStyle.BorderWidth = New Unit(1, UnitType.Pixel)
cell.SetStyle(style)
```

### أنظر أيضا

* مساحة الاسم [Aspose.Cells.GridWeb](../../aspose.cells.gridweb)
* المجسم [Aspose.Cells.GridWeb](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->