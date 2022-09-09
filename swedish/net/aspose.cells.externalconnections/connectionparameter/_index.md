---
title: ConnectionParameter
second_title: Aspose.Cells för .NET API-referens
description: Anger egenskaper för alla parametrar som används med externa dataanslutningar Parametrar är giltiga för ODBC och webbfrågor.
type: docs
weight: 3240
url: /sv/net/aspose.cells.externalconnections/connectionparameter/
---
## ConnectionParameter class

Anger egenskaper för alla parametrar som används med externa dataanslutningar Parametrar är giltiga för ODBC och webbfrågor.

```csharp
public class ConnectionParameter
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CellReference](../../aspose.cells.externalconnections/connectionparameter/cellreference) { get; set; } | Cellreferens som anger vilken cells värde som ska användas för frågeparametern. Används endast när parameterType är cell. |
| [Name](../../aspose.cells.externalconnections/connectionparameter/name) { get; set; } | Namnet på parametern. |
| [Prompt](../../aspose.cells.externalconnections/connectionparameter/prompt) { get; set; } | Promptsträng för parametern. Presenteras för kalkylarksanvändaren tillsammans med ingångsgränssnittet för att samla in parametervärdet innan den externa data uppdateras. Används endast när parameterType = prompt. |
| [RefreshOnChange](../../aspose.cells.externalconnections/connectionparameter/refreshonchange) { get; set; } | Flagga som anger om frågan ska uppdateras automatiskt när innehållet i en cell som tillhandahåller parametervärdet ändras. Om det är sant uppdateras extern data med det nya parametervärdet varje gång det sker en ändring. Om det är falskt uppdateras externa data endast när användaren begär det, eller så utlöser någon annan händelse uppdatering (t.ex. när arbetsboken öppnas). |
| [SqlType](../../aspose.cells.externalconnections/connectionparameter/sqltype) { get; set; } | SQL-datatyp för parametern. Endast giltigt för ODBC-källor. |
| [Type](../../aspose.cells.externalconnections/connectionparameter/type) { get; set; } | Typ av parameter som används. Om parameterType=värde, kommer värdet från boolean, double, integer, eller sträng att användas. I det här fallet förväntas det att endast en av {boolean, double, integer eller string} kommer att anges. |
| [Value](../../aspose.cells.externalconnections/connectionparameter/value) { get; set; } | Icke-heltals numeriskt värde, heltalsvärde, strängvärde eller booleskt värde som ska användas som frågeparameter. Används endast när parameterType är value. |

### Se även

* namnutrymme [Aspose.Cells.ExternalConnections](../../aspose.cells.externalconnections)
* hopsättning [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->