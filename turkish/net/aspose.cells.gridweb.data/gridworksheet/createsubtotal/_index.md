---
title: CreateSubtotal
second_title: Aspose.Cells for .NET API Referansı
description: Sayfada ara toplam oluşturur.
type: docs
weight: 490
url: /tr/net/aspose.cells.gridweb.data/gridworksheet/createsubtotal/
---
## CreateSubtotal(int, int, int, SubtotalFunction, int[], string, GridTableItemStyle, GridTableItemStyle, NumberType, string) {#createsubtotal_1}

Sayfada ara toplam oluşturur.

```csharp
public void CreateSubtotal(int columnNameRowIndex, int dataRows, int groupByColumnIndex, 
    SubtotalFunction subtotalFunction, int[] subtotalColumnIndexList, string functionLabel, 
    GridTableItemStyle grandCellStyle, GridTableItemStyle subtotalCellStyle, NumberType numberType, 
    string customString)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| columnNameRowIndex | Int32 | Sütun adı satırının satır dizini. |
| dataRows | Int32 | Veri satırlarının sayısı. |
| groupByColumnIndex | Int32 | Gruplandırılacak sütunun sütun dizini. |
| subtotalFunction | SubtotalFunction | Ara toplam işlev türü. |
| subtotalColumnIndexList | Int32[] | Alt toplamı alınacak sütun dizinleri. |
| functionLabel | String | Ara toplam fonksiyonunun etiketi. |
| grandCellStyle | GridTableItemStyle | Büyük toplam çizgisinin stili. |
| subtotalCellStyle | GridTableItemStyle | Ara toplam çizgisinin stili. |
| numberType | NumberType | Ara toplam sonuç hücrelerinin sayı türü. |
| customString | String | Ara toplam sonuç hücrelerinin özel biçim dizesi. Boş olabilir. |

### Ayrıca bakınız

* enum [SubtotalFunction](../../subtotalfunction)
* class [GridTableItemStyle](../../../aspose.cells.gridweb/gridtableitemstyle)
* enum [NumberType](../../numbertype)
* class [GridWorksheet](../../gridworksheet)
* ad alanı [Aspose.Cells.GridWeb.Data](../../gridworksheet)
* toplantı [Aspose.Cells.GridWeb](../../../)

---

## CreateSubtotal(int, int, int, SubtotalFunction, int[]) {#createsubtotal}

Sayfada ara toplam oluşturur.

```csharp
public void CreateSubtotal(int columnNameRowIndex, int dataRows, int groupByColumnIndex, 
    SubtotalFunction subtotalFunction, int[] subtotalColumnIndexList)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| columnNameRowIndex | Int32 | Sütun adı satırının satır dizini. |
| dataRows | Int32 | Veri satırlarının sayısı. |
| groupByColumnIndex | Int32 | Gruplandırılacak sütunun sütun dizini. |
| subtotalFunction | SubtotalFunction | Ara toplam işlev türü. |
| subtotalColumnIndexList | Int32[] | Alt toplamı alınacak sütun dizinleri. |

### Ayrıca bakınız

* enum [SubtotalFunction](../../subtotalfunction)
* class [GridWorksheet](../../gridworksheet)
* ad alanı [Aspose.Cells.GridWeb.Data](../../gridworksheet)
* toplantı [Aspose.Cells.GridWeb](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridWeb.dll -->