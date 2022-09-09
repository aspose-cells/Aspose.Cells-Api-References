---
title: GetPrecedents
second_title: Aspose.Cells för .NET API-referens
description: Får alla referenser som visas i den här cellens formel.
type: docs
weight: 470
url: /sv/net/aspose.cells/cell/getprecedents/
---
## Cell.GetPrecedents method

Får alla referenser som visas i den här cellens formel.

```csharp
public ReferredAreaCollection GetPrecedents()
```

### Returvärde

Samling av alla referenser som förekommer i denna cells formel.

### Anmärkningar

Returnerar null om detta inte är en formelcell.Alla referenser som förekommer i den här cellens formel kommer att returneras oavsett om de refereras till eller inte under beräkningen. Till exempel, även om cell A2 i formeln "=OM(TRUE,A1,A2)" inte används under beräkningen, är den fortfarande tas som formelns prejudikat. För att få de referenser som endast påverkar beräkningen, använd[`GetPrecedentsInCalculation`](../getprecedentsincalculation).

### Exempel

```csharp
[C#]

Workbook workbook = new Workbook();
Cells cells = workbook.Worksheets[0].Cells;
cells["A1"].Formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!A1";
ReferredAreaCollection areas = cells["A1"].GetPrecedents();
for (int i = 0; i < areas.Count; i++)
{
     ReferredArea area = areas[i];
     StringBuilder stringBuilder = new StringBuilder();
     if (area.IsExternalLink)
     {
         stringBuilder.Append("[");
         stringBuilder.Append(area.ExternalFileName);
         stringBuilder.Append("]");
     }
     stringBuilder.Append(area.SheetName);
     stringBuilder.Append("!");
     stringBuilder.Append(CellsHelper.CellIndexToName(area.StartRow, area.StartColumn));
     if (area.IsArea)
     {
         stringBuilder.Append(":");
         stringBuilder.Append(CellsHelper.CellIndexToName(area.EndRow, area.EndColumn));
     }
     Console.WriteLine(stringBuilder.ToString());
}

[Visual Basic]

Dim workbook As Workbook = New Workbook()
Dim cells As Cells = workbook.Worksheets(0).Cells
cells("A1").Formula = "= B1 + SUM(B1:B10) + [Book1.xls]Sheet1!A1"
Dim areas As ReferredAreaCollection = cells("A1").GetPrecedents()
For i As Integer = 0 To areas.Count - 1
    Dim area As ReferredArea = areas(i)
    Dim stringBuilder As StringBuilder = New StringBuilder()
    If (area.IsExternalLink) Then
        stringBuilder.Append("[")
        stringBuilder.Append(area.ExternalFileName)
       stringBuilder.Append("]")
    End If
    stringBuilder.Append(area.SheetName)
    stringBuilder.Append("!")
    stringBuilder.Append(CellsHelper.CellIndexToName(area.StartRow, area.StartColumn))
    If (area.IsArea) Then
        stringBuilder.Append(":")
        stringBuilder.Append(CellsHelper.CellIndexToName(area.EndRow, area.EndColumn))
    End If
    Console.WriteLine(stringBuilder.ToString())
Next
```

### Se även

* class [ReferredAreaCollection](../../referredareacollection)
* class [Cell](../../cell)
* namnutrymme [Aspose.Cells](../../cell)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->