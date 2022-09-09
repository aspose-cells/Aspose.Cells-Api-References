---
title: Add
second_title: Aspose.Cells für .NET-API-Referenz
description: Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.
type: docs
weight: 30
url: /de/net/aspose.cells.gridweb.data/gridhyperlinkcollection/add/
---
## Add(int, int, int, int, string) {#add}

Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.

```csharp
public int Add(int firstRow, int firstColumn, int totalRows, int totalColumns, string address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstRow | Int32 | Erste Zeile des Hyperlink-Bereichs. |
| firstColumn | Int32 | Erste Spalte des Hyperlink-Bereichs. |
| totalRows | Int32 | Anzahl der Zeilen in diesem Hyperlinkbereich. |
| totalColumns | Int32 | Anzahl der Spalten dieses Hyperlinkbereichs. |
| address | String | Adresse des Hyperlinks. |

### Rückgabewert

Hyperlink Objektindex.

### Beispiele

```csharp
[C#]

Worksheet worksheet = excel.Worksheets[0];
worksheet.Hyperlinks.Add("A4", 1, 1, "http://www.aspose.com");
worksheet.Hyperlinks.Add("A5", 1, 1, "c:\\book1.xls");

[Visual Basic]

Dim worksheet as Worksheet = excel.Worksheets(0)
worksheet.Hyperlinks.Add("A4", 1, 1, "http://www.aspose.com")
worksheet.Hyperlinks.Add("A5", 1, 1, "c:\\book1.xls")

```

### Siehe auch

* class [GridHyperlinkCollection](../../gridhyperlinkcollection)
* namensraum [Aspose.Cells.GridWeb.Data](../../gridhyperlinkcollection)
* Montage [Aspose.Cells.GridWeb](../../../)

---

## Add(string, int, int, string) {#add_1}

Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.

```csharp
public int Add(string cellName, int totalRows, int totalColumns, string address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellName | String | Zellenname. |
| totalRows | Int32 | Anzahl der Zeilen in diesem Hyperlinkbereich. |
| totalColumns | Int32 | Anzahl der Spalten dieses Hyperlinkbereichs. |
| address | String | Adresse des Hyperlinks. |

### Rückgabewert

[`GridHyperlink`](../../gridhyperlink) Objektindex.

### Siehe auch

* class [GridHyperlinkCollection](../../gridhyperlinkcollection)
* namensraum [Aspose.Cells.GridWeb.Data](../../gridhyperlinkcollection)
* Montage [Aspose.Cells.GridWeb](../../../)

---

## Add(string, string) {#add_2}

Fügt einen Hyperlink zu einer angegebenen Zelle hinzu .

```csharp
public int Add(string cellName, string address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cellName | String | Zellenname. |
| address | String | Adresse des Hyperlinks. |

### Rückgabewert

[`GridHyperlink`](../../gridhyperlink) Objektindex.

### Siehe auch

* class [GridHyperlinkCollection](../../gridhyperlinkcollection)
* namensraum [Aspose.Cells.GridWeb.Data](../../gridhyperlinkcollection)
* Montage [Aspose.Cells.GridWeb](../../../)

---

## Add(string, string, string, string, string) {#add_3}

Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.

```csharp
public int Add(string startCellName, string endCellName, string address, string textToDisplay, 
    string screenTip)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCellName | String | Die obere linke Zelle des Bereichs. |
| endCellName | String | Die untere rechte Zelle des Bereichs. |
| address | String | Adresse des Hyperlinks. |
| textToDisplay | String | Der Text, der für den angegebenen Hyperlink angezeigt werden soll. |
| screenTip | String | Der QuickInfo-Text für den angegebenen Hyperlink. |

### Rückgabewert

[`GridHyperlink`](../../gridhyperlink) Objektindex.

### Siehe auch

* class [GridHyperlinkCollection](../../gridhyperlinkcollection)
* namensraum [Aspose.Cells.GridWeb.Data](../../gridhyperlinkcollection)
* Montage [Aspose.Cells.GridWeb](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->