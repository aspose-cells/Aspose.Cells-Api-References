---
title: AddCheckBox
second_title: Référence de l'API Aspose.Cells pour .NET
description: Ajoute une case à cocher à la feuille de calcul.
type: docs
weight: 70
url: /fr/net/aspose.cells.drawing/shapecollection/addcheckbox/
---
## ShapeCollection.AddCheckBox method

Ajoute une case à cocher à la feuille de calcul.

```csharp
public CheckBox AddCheckBox(int upperLeftRow, int top, int upperLeftColumn, int left, int height, 
    int width)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| upperLeftRow | Int32 | Index de ligne en haut à gauche. |
| top | Int32 | Représente le décalage vertical de la case à cocher par rapport à sa ligne de gauche, en unité de pixel. |
| upperLeftColumn | Int32 | Index de la colonne en haut à gauche. |
| left | Int32 | Représente le décalage horizontal de la zone de texte par rapport à sa colonne de gauche, en unité de pixel. |
| height | Int32 | Hauteur de la zone de texte, en unité de pixel. |
| width | Int32 | Largeur de la zone de texte, en unité de pixel. |

### Return_Value

Le nouvel index d'objet CheckBox.

### Exemples

```csharp

[C#]

// ajouter une case à cocher
CheckBox checkBox = shapes.AddCheckBox(1, 0, 1, 0, 100, 50);
```

### Voir également

* class [CheckBox](../../checkbox)
* class [ShapeCollection](../../shapecollection)
* espace de noms [Aspose.Cells.Drawing](../../shapecollection)
* Assemblée [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->