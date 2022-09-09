---
title: CheckExcelRestriction
second_title: Aspose.Cells för .NET API-referens
description: Om kontrollera begränsningen av excel-fil när användaren ändrar cellrelaterade objekt. Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K. När du matar in ett värde längre än 32K såsom av Cell.PutValuesträng om detta egenskapen är sant får du ett undantag. Om den här egenskapen är falsk accepterar vi ditt inmatade strängvärde som cellens värde så att du senare kan mata ut hela strängvärdet för andra filformat som CSV. Men om du har angett ett sådant värde som är ogiltigt för Excel-filformat du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade excel-filen.
type: docs
weight: 50
url: /sv/net/aspose.cells/loadoptions/checkexcelrestriction/
---
## LoadOptions.CheckExcelRestriction property

Om kontrollera begränsningen av excel-fil när användaren ändrar cellrelaterade objekt. Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K. När du matar in ett värde längre än 32K såsom av Cell.PutValue(sträng), om detta egenskapen är sant får du ett undantag. Om den här egenskapen är falsk accepterar vi ditt inmatade strängvärde som cellens värde så att du senare kan mata ut hela strängvärdet för andra filformat som CSV. Men om du har angett ett sådant värde som är ogiltigt för Excel-filformat, du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade excel-filen.

```csharp
public bool CheckExcelRestriction { get; set; }
```

### Se även

* class [LoadOptions](../../loadoptions)
* namnutrymme [Aspose.Cells](../../loadoptions)
* hopsättning [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->