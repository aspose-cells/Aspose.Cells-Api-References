---
title: ConnectionParameter
second_title: Référence de l'API Aspose.Cells pour .NET
description: Spécifie les propriétés de tous les paramètres utilisés avec les connexions de données externes Les paramètres sont valides pour les requêtes ODBC et Web.
type: docs
weight: 3240
url: /fr/net/aspose.cells.externalconnections/connectionparameter/
---
## ConnectionParameter class

Spécifie les propriétés de tous les paramètres utilisés avec les connexions de données externes Les paramètres sont valides pour les requêtes ODBC et Web.

```csharp
public class ConnectionParameter
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CellReference](../../aspose.cells.externalconnections/connectionparameter/cellreference) { get; set; } | Référence de cellule indiquant la valeur de cellule à utiliser pour le paramètre de requête. Utilisé uniquement lorsque le type de paramètre est cell. |
| [Name](../../aspose.cells.externalconnections/connectionparameter/name) { get; set; } | Le nom du paramètre. |
| [Prompt](../../aspose.cells.externalconnections/connectionparameter/prompt) { get; set; } | Chaîne d'invite pour le paramètre. Présenté à l'utilisateur de la feuille de calcul avec l'interface utilisateur d'entrée pour collecter la valeur du paramètre avant d'actualiser les données externes. Utilisé uniquement lorsque parameterType = prompt. |
| [RefreshOnChange](../../aspose.cells.externalconnections/connectionparameter/refreshonchange) { get; set; } | Indicateur indiquant si la requête doit s'actualiser automatiquement lorsque le contenu d'une cellule qui fournit la valeur du paramètre change. Si la valeur est true, les données externes sont actualisées à l'aide de la nouvelle valeur de paramètre à chaque modification. Si false, les données externes ne sont actualisées qu'à la demande de l'utilisateur, ou d'autres événements déclenchent l'actualisation (par exemple, classeur ouvert). |
| [SqlType](../../aspose.cells.externalconnections/connectionparameter/sqltype) { get; set; } | Type de données SQL du paramètre. Valable uniquement pour les sources ODBC. |
| [Type](../../aspose.cells.externalconnections/connectionparameter/type) { get; set; } | Type de paramètre utilisé. Si le type de paramètre=valeur, alors la valeur parmi booléen, double, entier, ou chaîne sera utilisée. Dans ce cas, on s'attend à ce qu'un seul des {booléen, double, entier ou chaîne} soit spécifié. |
| [Value](../../aspose.cells.externalconnections/connectionparameter/value) { get; set; } | Valeur numérique non entière, valeur entière, valeur de chaîne ou valeur booléenne à utiliser comme paramètre de requête. Utilisé uniquement lorsque parameterType est value. |

### Voir également

* espace de noms [Aspose.Cells.ExternalConnections](../../aspose.cells.externalconnections)
* Assemblée [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->