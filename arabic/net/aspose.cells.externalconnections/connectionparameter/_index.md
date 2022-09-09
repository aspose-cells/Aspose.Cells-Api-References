---
title: ConnectionParameter
second_title: Aspose.Cells لمرجع .NET API
description: تحديد خصائص حول أي معلمات مستخدمة مع اتصالات البيانات الخارجية المعلمات صالحة لاستعلامات ODBC والويب .
type: docs
weight: 3240
url: /ar/net/aspose.cells.externalconnections/connectionparameter/
---
## ConnectionParameter class

تحديد خصائص حول أي معلمات مستخدمة مع اتصالات البيانات الخارجية المعلمات صالحة لاستعلامات ODBC والويب .

```csharp
public class ConnectionParameter
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CellReference](../../aspose.cells.externalconnections/connectionparameter/cellreference) { get; set; } | يشير مرجع الخلية إلى قيمة الخلية المراد استخدامها لمعلمة الاستعلام. يستخدم فقط عندما تكون المعلمة نوع الخلية. |
| [Name](../../aspose.cells.externalconnections/connectionparameter/name) { get; set; } | اسم المعلمة . |
| [Prompt](../../aspose.cells.externalconnections/connectionparameter/prompt) { get; set; } | سلسلة مطالبة للمعلمة. يتم تقديمها إلى مستخدم جدول البيانات مع إدخال واجهة المستخدم لتجميع قيمة المعلمة قبل تحديث البيانات الخارجية. يستخدم فقط عندما parameterType = موجه . |
| [RefreshOnChange](../../aspose.cells.externalconnections/connectionparameter/refreshonchange) { get; set; } | علامة تشير إلى ما إذا كان يجب تحديث الاستعلام تلقائيًا عند تغيير محتويات خلية توفر قيمة المعلمة. إذا كان هذا صحيحًا ، فسيتم تحديث البيانات الخارجية باستخدام قيمة المعلمة الجديدة في كل مرة يحدث فيها تغيير. في حالة الخطأ ، يتم تحديث البيانات الخارجية فقط عند طلب المستخدم ، أو تحديث بعض مشغلات الأحداث الأخرى (على سبيل المثال ، تم فتح المصنف). |
| [SqlType](../../aspose.cells.externalconnections/connectionparameter/sqltype) { get; set; } | نوع بيانات SQL للمعلمة. صالح فقط لمصادر ODBC. |
| [Type](../../aspose.cells.externalconnections/connectionparameter/type) { get; set; } | نوع المعلمة المستخدمة. إذا كانت المعلمة Type = القيمة ، فسيتم استخدام القيمة المنطقية أو المزدوجة أو الصحيحة أو أو السلسلة. في هذه الحالة ، من المتوقع أن يتم تحديد واحد فقط من {منطقي أو مزدوج أو عدد صحيح أو سلسلة}. |
| [Value](../../aspose.cells.externalconnections/connectionparameter/value) { get; set; } | قيمة عددية غير صحيحة أو قيمة عدد صحيح أو قيمة سلسلة أو قيمة منطقية لاستخدامها كمعامل استعلام. يستخدم فقط عندما تكون قيمة المعلمة هي القيمة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Cells.ExternalConnections](../../aspose.cells.externalconnections)
* المجسم [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->