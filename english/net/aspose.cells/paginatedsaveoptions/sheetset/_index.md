---
title: SheetSet
second_title: Aspose.Cells for .NET API Reference
description: Gets or sets the sheets to render. Default is all visible sheets in the workbook Visibleaspose.cells.rendering/sheetset/visible.
type: docs
weight: 160
url: /net/aspose.cells/paginatedsaveoptions/sheetset/
---
## PaginatedSaveOptions.SheetSet property

Gets or sets the sheets to render. Default is all visible sheets in the workbook: [`Visible`](../../../aspose.cells.rendering/sheetset/visible).

```csharp
public SheetSet SheetSet { get; set; }
```

### Examples

The following code only renders active sheet to pdf.

```csharp
Workbook workbook = new Workbook("Book1.xlsx");

int activeSheetIndex = workbook.Worksheets.ActiveSheetIndex;

PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();
//set active sheet index to sheet set.
pdfSaveOptions.SheetSet = new SheetSet(new int[] { activeSheetIndex });
workbook.Save("output.pdf", pdfSaveOptions);
```

### See Also

* class [SheetSet](../../../aspose.cells.rendering/sheetset)
* class [PaginatedSaveOptions](../../paginatedsaveoptions)
* namespace [Aspose.Cells](../../paginatedsaveoptions)
* assembly [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->