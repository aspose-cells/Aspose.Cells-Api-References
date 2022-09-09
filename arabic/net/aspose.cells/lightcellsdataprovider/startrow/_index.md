---
title: StartRow
second_title: Aspose.Cells لمرجع .NET API
description: يبدأ في حفظ البيانات لصف واحد.
type: docs
weight: 50
url: /ar/net/aspose.cells/lightcellsdataprovider/startrow/
---
## LightCellsDataProvider.StartRow method

يبدأ في حفظ البيانات لصف واحد.

```csharp
public void StartRow(Row row)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| row | Row | كائن صف للتنفيذ لملء البيانات. فهرس الصف الخاص به هو القيمة التي تم إرجاعها لآخر مكالمة لـ[`NextRow`](../nextrow) . إذا تمت تهيئة الصف في نموذج الخلايا الداخلية ، فسيتم استخدام كائن الصف الحالي . وإلا فسيتم استخدام كائن صف مؤقت للتنفيذ لتعبئة البيانات. |

### ملاحظات

سيتم استدعاؤه في بداية حفظ صف وبيانات خلاياه. إذا كان الصف الحالي يحتوي على بعض الخصائص المخصصة مثل الارتفاع ، النمط ، ... إلخ ، يجب تعيين هذه الخصائص لكائن الصف المحدد هنا .

### أنظر أيضا

* class [Row](../../row)
* interface [LightCellsDataProvider](../../lightcellsdataprovider)
* مساحة الاسم [Aspose.Cells](../../lightcellsdataprovider)
* المجسم [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->