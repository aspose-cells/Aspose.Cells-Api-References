---
title: Border
second_title: Référence de l'API Aspose.Cells pour .NET
description: Encapsule lobjet qui représente la bordure de la cellule.
type: docs
weight: 140
url: /fr/net/aspose.cells/border/
---
## Border class

Encapsule l'objet qui représente la bordure de la cellule.

```csharp
public class Border
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ArgbColor](../../aspose.cells/border/argbcolor) { get; set; } | Obtient et définit la couleur avec une valeur ARGB 32 bits. |
| [Color](../../aspose.cells/border/color) { get; set; } | Obtient ou définit leColor de la frontière. |
| [LineStyle](../../aspose.cells/border/linestyle) { get; set; } | Obtient ou définit le type de bordure de cellule. |
| [ThemeColor](../../aspose.cells/border/themecolor) { get; set; } | Obtient et définit la couleur du thème de la bordure. |

### Exemples

```csharp
[C#]
Workbook workbook = new Workbook();

WorksheetCollection sheets = workbook.Worksheets;
Cell cell = sheets[0].Cells["A1"];

Style style = cell.GetStyle();
// Définir le style et la couleur de la bordure supérieure
Border border = style.Borders[BorderType.TopBorder];
border.LineStyle = CellBorderType.Medium;
border.Color = Color.Red;
cell.SetStyle(style);

[Visual Basic]
Dim workbook as Workbook  = New Workbook()

Dim sheets as WorksheetCollection  = workbook.Worksheets
Cell cell = sheets(0).Cells("A1");
Dim style as Style = cell.GetStyle()
'Définir le style et la couleur de la bordure supérieure
Dim border as Border = style.Borders(BorderType.TopBorder)
border.LineStyle = CellBorderType.Medium
border.Color = Color.Red
cell.SetStyle(style);
```

### Voir également

* espace de noms [Aspose.Cells](../../aspose.cells)
* Assemblée [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->