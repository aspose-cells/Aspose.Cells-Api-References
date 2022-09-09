---
title: ExportDataTable
second_title: Riferimento alle API di Aspose.Cells per .NET
description: Esporta i dati nella raccolta Cells di un foglio di lavoro in un oggetto DataTable specificato.
type: docs
weight: 650
url: /it/net/aspose.cells.griddesktop/worksheet/exportdatatable/
---
## ExportDataTable(DataTable, int, int, int, int, bool) {#exportdatatable_1}

Esporta i dati nella raccolta Cells di un foglio di lavoro in un oggetto DataTable specificato.

```csharp
public DataTable ExportDataTable(DataTable dataTable, int startRow, int startColumn, int rows, 
    int columns, bool isVertical)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataTable | DataTable | L'oggetto DataTable in cui esporta i dati. |
| startRow | Int32 | Il numero di riga della prima cella da esportare. |
| startColumn | Int32 | Il numero di colonna della prima cella da esportare. |
| rows | Int32 | Numero di righe da importare. |
| columns | Int32 | Numero di colonne da importare. |
| isVertical | Boolean | True se una riga nel controllo rappresenta una riga in DataTable. False se una colonna nel controllo rappresenta una riga in DataTable. |

### Valore di ritorno

Oggetto DataTable esportato.

### Osservazioni

Il metodo consente prima di creare un oggetto DataTable. Quindi esporta i dati nell'oggetto DataTable. Se dataTable non è impostato come valido, il metodo restituirà un nuovo oggetto DataTable chiamando il metodo di overload 'Export(bool exportColumnName, bool isVertical)'.

### Esempi

```csharp
[C#]

DataTable dataTable = new DataTable();
dataTable.Columns.Add("Column a",System.Type.GetType("System.String"));
dataTable.Columns.Add("Column b");
dataTable.Columns.Add("Column c");
dataTable.Columns.Add("Column d",System.Type.GetType("System.Double"));
dataTable.Columns.Add("Column e",System.Type.GetType("System.Int32"));
dataTable.Columns.Add("Column f",System.Type.GetType("System.Int32"));
DataTable exportTable = gridDesktop.Worksheets[0].Export(dataTable,1,0,10,6,true);
DataGrid1.SetDataBinding(exportTable, null);

[VB]

Dim dataTable As DataTable =  New DataTable() 
dataTable.Columns.Add("Column a",System.Type.GetType("System.String"))
dataTable.Columns.Add("Column b")
dataTable.Columns.Add("Column c")
dataTable.Columns.Add("Column d",System.Type.GetType("System.Double"))
dataTable.Columns.Add("Column e",System.Type.GetType("System.Int32"))
dataTable.Columns.Add("Column f",System.Type.GetType("System.Int32"))
Dim exportTable As DataTable =  GridDesktop.Worksheets(0).Export(dataTable,1,0,10,6,True) 
DataGrid1.SetDataBinding(exportTable)
```

### Guarda anche

* class [Worksheet](../../worksheet)
* spazio dei nomi [Aspose.Cells.GridDesktop](../../worksheet)
* assemblea [Aspose.Cells.GridDesktop](../../../)

---

## ExportDataTable(int, int, int, int, bool, bool) {#exportdatatable}

Esporta i dati nella raccolta Cells di un foglio di lavoro in un nuovo oggetto DataTable.

```csharp
public DataTable ExportDataTable(int startRow, int startColumn, int rows, int columns, 
    bool exportColumnName, bool isVertical)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startRow | Int32 | Il numero di riga della prima cella da esportare. |
| startColumn | Int32 | Il numero di colonna della prima cella da esportare. |
| rows | Int32 | Numero di righe da importare. |
| columns | Int32 | Numero di colonne da importare. |
| exportColumnName | Boolean | Indica se i dati nella prima riga vengono esportati nel nome della colonna di DataTable. |
| isVertical | Boolean | True se una riga nel controllo rappresenta una riga in DataTable. False se una colonna nel controllo rappresenta una riga in DataTable. |

### Valore di ritorno

Oggetto DataTable esportato.

### Esempi

```csharp
[C#]

DataTable exportTable = gridDesktop.Worksheets[0].Export(0,0,10,2,true,false);
DataGrid1.SetDataBinding(exportTable, null);

[VB]

Dim exportTable As DataTable =  GridDesktop.Worksheets(0).Export(0,0,10,2,True,False) 
DataGrid1.SetDataBinding(exportTable)
```

### Guarda anche

* class [Worksheet](../../worksheet)
* spazio dei nomi [Aspose.Cells.GridDesktop](../../worksheet)
* assemblea [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->