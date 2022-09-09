---
title: WebBorderStyle
second_title: Référence de l'API Aspose.Cells pour .NET
description: Encapsule le style du tableau Web ou de la bordure de cellule.
type: docs
weight: 930
url: /fr/net/aspose.cells.gridweb/webborderstyle/
---
## WebBorderStyle class

Encapsule le style du tableau Web ou de la bordure de cellule.

```csharp
public class WebBorderStyle
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WebBorderStyle](webborderstyle)() | Constructeur par défaut. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BorderColor](../../aspose.cells.gridweb/webborderstyle/bordercolor) { get; set; } | Obtient ou définit la couleur de la bordure. Veuillez vous référer à System.Drawing.Color struct. |
| [BorderStyle](../../aspose.cells.gridweb/webborderstyle/borderstyle) { get; set; } | Obtient ou définit le style de la bordure. Veuillez vous référer au document .NET SDK sur System.Web.UI.WebControls.BorderStyle enum. |
| [BorderWidth](../../aspose.cells.gridweb/webborderstyle/borderwidth) { get; set; } | Obtient ou définit la largeur de la bordure. Veuillez vous référer à System.Web.UI.WebControls.Unit struct. |

## Méthodes

| Nom | La description |
| --- | --- |
| [CopyFrom](../../aspose.cells.gridweb/webborderstyle/copyfrom)(WebBorderStyle) | Copies d'un autre objet de style. |
| override [GetHashCode](../../aspose.cells.gridweb/webborderstyle/gethashcode)() |  |

### Remarques

Veuillez vous référer au document .NET SDK pour plus d'informations sur l'espace de noms System.Web.UI.WebControls.

### Exemples

```csharp
[C#]
	WebCell cell1 = GridWeb1.WebWorksheets[0].Cells["A1"];
	cell1.Style.LeftBorderStyle.BorderColor = System.Drawing.Color.Red;
	cell1.Style.LeftBorderStyle.BorderStyle = System.Web.UI.WebControls.BorderStyle.Solid;
	cell1.Style.LeftBorderStyle.BorderWidth = new System.Web.UI.WebControls.Unit(16, System.Web.UI.WebControls.UnitType.Point);

[Visual Basic]
	Dim cell1 As WebCell =  GridWeb1.WebWorksheets(0).Cells("A1")
	cell1.Style.LeftBorderStyle.BorderColor = System.Drawing.Color.Red
	cell1.Style.LeftBorderStyle.BorderStyle = System.Web.UI.WebControls.BorderStyle.Solid
	cell1.Style.LeftBorderStyle.BorderWidth = New System.Web.UI.WebControls.Unit(16, System.Web.UI.WebControls.UnitType.Point)
```

### Voir également

* espace de noms [Aspose.Cells.GridWeb](../../aspose.cells.gridweb)
* Assemblée [Aspose.Cells.GridWeb](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->