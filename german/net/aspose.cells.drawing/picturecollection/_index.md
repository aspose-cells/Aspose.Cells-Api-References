---
title: PictureCollection
second_title: Aspose.Cells für .NET-API-Referenz
description: Kapselt eine Sammlung vonPicture./picture Objekte.
type: docs
weight: 2490
url: /de/net/aspose.cells.drawing/picturecollection/
---
## PictureCollection class

Kapselt eine Sammlung von[`Picture`](../picture) Objekte.

```csharp
public class PictureCollection : CollectionBase<Picture>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Capacity](../../aspose.cells/collectionbase`1/capacity) { get; set; } |  |
| [Count](../../aspose.cells/collectionbase`1/count) { get; } |  |
| [Item](../../aspose.cells.drawing/picturecollection/item) { get; } | Ruft die ab[`Picture`](../picture) Element am angegebenen Index. |
| [Item](../../aspose.cells/collectionbase`1/item) { get; set; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.cells.drawing/picturecollection/add#add_2)(int, int, Stream) | Fügt der Sammlung ein Bild hinzu. |
| [Add](../../aspose.cells.drawing/picturecollection/add#add_4)(int, int, string) | Fügt der Sammlung ein Bild hinzu. |
| [Add](../../aspose.cells.drawing/picturecollection/add#add)(int, int, int, int, Stream) | Fügt der Sammlung ein Bild hinzu. |
| [Add](../../aspose.cells.drawing/picturecollection/add#add_1)(int, int, int, int, string) | Fügt der Sammlung ein Bild hinzu. |
| [Add](../../aspose.cells.drawing/picturecollection/add#add_3)(int, int, Stream, int, int) | Fügt der Sammlung ein Bild hinzu. |
| [Add](../../aspose.cells.drawing/picturecollection/add#add_5)(int, int, string, int, int) | Fügt der Sammlung ein Bild hinzu. |
| [BinarySearch](../../aspose.cells/collectionbase`1/binarysearch)(Picture) |  |
| [BinarySearch](../../aspose.cells/collectionbase`1/binarysearch)(Picture, IComparer&lt;Picture&gt;) |  |
| [BinarySearch](../../aspose.cells/collectionbase`1/binarysearch)(int, int, Picture, IComparer&lt;Picture&gt;) |  |
| [Clear](../../aspose.cells.drawing/picturecollection/clear#clear)() | Alle Bilder löschen. (2 methods) |
| [Contains](../../aspose.cells/collectionbase`1/contains)(Picture) |  |
| [CopyTo](../../aspose.cells/collectionbase`1/copyto)(Picture[]) |  |
| [CopyTo](../../aspose.cells/collectionbase`1/copyto)(Picture[], int) |  |
| [CopyTo](../../aspose.cells/collectionbase`1/copyto)(int, Picture[], int, int) |  |
| [Exists](../../aspose.cells/collectionbase`1/exists)(Predicate&lt;Picture&gt;) |  |
| [Find](../../aspose.cells/collectionbase`1/find)(Predicate&lt;Picture&gt;) |  |
| [FindAll](../../aspose.cells/collectionbase`1/findall)(Predicate&lt;Picture&gt;) |  |
| [FindIndex](../../aspose.cells/collectionbase`1/findindex)(Predicate&lt;Picture&gt;) |  |
| [FindIndex](../../aspose.cells/collectionbase`1/findindex)(int, Predicate&lt;Picture&gt;) |  |
| [FindIndex](../../aspose.cells/collectionbase`1/findindex)(int, int, Predicate&lt;Picture&gt;) |  |
| [FindLast](../../aspose.cells/collectionbase`1/findlast)(Predicate&lt;Picture&gt;) |  |
| [FindLastIndex](../../aspose.cells/collectionbase`1/findlastindex)(Predicate&lt;Picture&gt;) |  |
| [FindLastIndex](../../aspose.cells/collectionbase`1/findlastindex)(int, Predicate&lt;Picture&gt;) |  |
| [FindLastIndex](../../aspose.cells/collectionbase`1/findlastindex)(int, int, Predicate&lt;Picture&gt;) |  |
| [GetEnumerator](../../aspose.cells/collectionbase`1/getenumerator)() |  |
| [IndexOf](../../aspose.cells/collectionbase`1/indexof)(Picture) |  |
| [IndexOf](../../aspose.cells/collectionbase`1/indexof)(Picture, int) |  |
| [IndexOf](../../aspose.cells/collectionbase`1/indexof)(Picture, int, int) |  |
| [LastIndexOf](../../aspose.cells/collectionbase`1/lastindexof)(Picture) |  |
| [LastIndexOf](../../aspose.cells/collectionbase`1/lastindexof)(Picture, int) |  |
| [LastIndexOf](../../aspose.cells/collectionbase`1/lastindexof)(Picture, int, int) |  |
| [RemoveAt](../../aspose.cells.drawing/picturecollection/removeat#removeat)(int) | Entfernen Sie Formen an dem bestimmten Index (2 methods) |

### Beispiele

```csharp

[C#]

//Instanziieren eines Workbook-Objekts
Workbook workbook = new Workbook();

//PictureCollection abrufen
PictureCollection pictures = workbook.Worksheets[0].Pictures;

// Mach dein Geschäft

//Speichern Sie die Excel-Datei.
workbook.Save("result.xlsx");
```

### Siehe auch

* class [CollectionBase&lt;T&gt;](../../aspose.cells/collectionbase-1)
* class [Picture](../picture)
* namensraum [Aspose.Cells.Drawing](../../aspose.cells.drawing)
* Montage [Aspose.Cells](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->