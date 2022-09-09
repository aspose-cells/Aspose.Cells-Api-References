---
title: Name
second_title: Référence de l'API Aspose.Cells pour .NET
description: Représente un nom défini pour une plage de cellules.
type: docs
weight: 4200
url: /fr/net/aspose.cells/name/
---
## Name class

Représente un nom défini pour une plage de cellules.

```csharp
public class Name
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Comment](../../aspose.cells/name/comment) { get; set; } | Obtient et définit le commentaire du nom. Ne s'applique qu'à Excel 2007. |
| [FullText](../../aspose.cells/name/fulltext) { get; } | Obtient le nom en texte intégral de l'objet avec le paramètre de portée. |
| [IsReferred](../../aspose.cells/name/isreferred) { get; } | Indique si ce nom est référencé par d'autres formules. |
| [IsVisible](../../aspose.cells/name/isvisible) { get; set; } | Indique si le nom est visible. |
| [R1C1RefersTo](../../aspose.cells/name/r1c1refersto) { get; set; } | Obtient ou définit une référence R1C1 du[`Name`](../name) . |
| [RefersTo](../../aspose.cells/name/refersto) { get; set; } | Renvoie ou définit la formule à laquelle le nom est défini pour faire référence, en commençant par un signe égal. |
| [SheetIndex](../../aspose.cells/name/sheetindex) { get; set; } | Indique que ce nom appartient au classeur ou à la feuille de calcul. 0 = nom global, sinon index de la feuille (base un) |
| [Text](../../aspose.cells/name/text) { get; set; } | Obtient le texte du nom de l'objet. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetRange](../../aspose.cells/name/getrange#getrange)() | Obtient la plage si ce nom fait référence à une plage. |
| [GetRange](../../aspose.cells/name/getrange#getrange_1)(bool) | Obtient la plage si ce nom fait référence à une plage |
| [GetRange](../../aspose.cells/name/getrange#getrange_2)(int, int, int) | Obtient la plage si ce nom fait référence à une plage. Si la référence de ce nom n'est pas absolue, la plage peut être différente pour différentes cellules. |
| [GetRanges](../../aspose.cells/name/getranges#getranges)() | Obtient toutes les plages référencées par ce nom. |
| [GetRanges](../../aspose.cells/name/getranges#getranges_1)(bool) | Obtient toutes les plages référencées par ce nom. |
| [GetReferredAreas](../../aspose.cells/name/getreferredareas)(bool) | Obtient toutes les références référencées par ce nom. |
| [GetRefersTo](../../aspose.cells/name/getrefersto#getrefersto)(bool, bool) | Obtenir la référence de ce Nom. |
| [GetRefersTo](../../aspose.cells/name/getrefersto#getrefersto_1)(bool, bool, int, int) | Obtenez la référence de ce nom en fonction de la cellule spécifiée. |
| [SetRefersTo](../../aspose.cells/name/setrefersto)(string, bool, bool) | Définir la référence de ce Nom. |
| override [ToString](../../aspose.cells/name/tostring)() | Renvoie une chaîne représentant l'objet Range actuel. |

### Exemples

```csharp

[C#]

//Instanciation d'un objet Workbook
Workbook workbook = new Workbook();
//Accéder à la première feuille de calcul du fichier Excel
Worksheet worksheet = workbook.Worksheets[0];
//Création d'une plage nommée
Range range = worksheet.Cells.CreateRange("B4", "G14");
//Définition du nom de la plage nommée
range.Name = "TestRange";
//Enregistrement du fichier Excel modifié au format par défaut (c'est-à-dire Excel 2000)
workbook.Save("output.xls");   

[Visual Basic]

'Instanciation d'un objet Workbook
Dim workbook As Workbook = New Workbook()
'Accéder à la première feuille de calcul du fichier Excel
Dim worksheet As Worksheet = workbook.Worksheets(0)
'Création d'une plage nommée
Dim range As Range = worksheet.Cells.CreateRange("B4", "G14")
'Définition du nom de la plage nommée
range.Name = "TestRange"
'Enregistrement du fichier Excel modifié au format par défaut (c'est-à-dire Excel 2000)
workbook.Save("output.xls")
```

### Voir également

* espace de noms [Aspose.Cells](../../aspose.cells)
* Assemblée [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->