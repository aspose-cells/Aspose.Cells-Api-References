---
title: AutoFill
second_title: Aspose.Cells för .NET API-referens
description: Fyller automatiskt målintervallet.
type: docs
weight: 220
url: /sv/net/aspose.cells/range/autofill/
---
## AutoFill(Range) {#autofill}

Fyller automatiskt målintervallet.

```csharp
public void AutoFill(Range target)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | Range | målområdet. |

### Exempel

```csharp

[C#]

//Instantiering av ett arbetsboksobjekt
Workbook workbook = new Workbook();
// Få de första kalkylbladscellerna.
Cells cells = workbook.Worksheets[0].Cells;
cells["A1"].PutValue(1);
cells["A2"].PutValue(2);
Aspose.Cells.Range source = cells.CreateRange("A1:A2");
Aspose.Cells.Range target = cells.CreateRange("A3:A10");
//fyll 3,4,5....10 till intervallet A3:A10
source.AutoFill(target);
//Spara Excel-filen
workbook.Save("book1.xlsm");

 [Visual Basic]

'Instantiera ett arbetsboksobjekt
Dim workbook As Workbook = New Workbook("Book1.xlsx")
// Få de första kalkylbladscellerna.
Dim cells as Cells = workbook.Worksheets[0].Cells
cells("A1").PutValue(1)
cells("A2").PutValue(2)
Dim source as Aspose.Cells.Range = cells.CreateRange("A1:A2")
Dim target as Aspose.Cells.Range = cells.CreateRange("A3:A10")
'fyll 3,4,5....10 till intervallet A3:A10
source.AutoFill(target)
'Spara Excel-filen
workbook.Save("book1.xlsm")
```

### Se även

* class [Range](../../range)
* namnutrymme [Aspose.Cells](../../range)
* hopsättning [Aspose.Cells](../../../)

---

## AutoFill(Range, AutoFillType) {#autofill_1}

Fyller automatiskt målintervallet.

```csharp
public void AutoFill(Range target, AutoFillType autoFillType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| target | Range | Det riktade intervallet. |
| autoFillType | AutoFillType | Den automatiska fyllningstypen. |

### Se även

* enum [AutoFillType](../../autofilltype)
* class [Range](../../range)
* namnutrymme [Aspose.Cells](../../range)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->