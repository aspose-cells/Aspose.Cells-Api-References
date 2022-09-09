---
title: GetDependentsInCalculation
second_title: Aspose.Cells für .NET-API-Referenz
description: Ruft alle Zellen ab deren berechnetes Ergebnis von einer bestimmten Zelle abhängt.
type: docs
weight: 710
url: /de/net/aspose.cells/cells/getdependentsincalculation/
---
## Cells.GetDependentsInCalculation method

Ruft alle Zellen ab, deren berechnetes Ergebnis von einer bestimmten Zelle abhängt.

```csharp
public IEnumerator GetDependentsInCalculation(int row, int column, bool recursive)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| row | Int32 | Zeilenindex der spezifischen Zelle |
| column | Int32 | Spaltenindex der spezifischen Zelle. |
| recursive | Boolean | Ob gibt die abhängigen Elemente zurück, die nicht direkt auf die spezifische Zelle verweisen , sondern auf andere Blätter dieser Zelle verweisen. |

### Rückgabewert

Enumerator zum Aufzählen aller Abhängigen (Zellobjekte)

### Bemerkungen

Um diese Methode zu verwenden, stellen Sie bitte sicher, dass die Arbeitsmappe mit dem wahren Wert für festgelegt wurde.[`EnableCalculationChain`](../../formulasettings/enablecalculationchain) und wurde mit dieser Einstellung vollständig berechnet. Wenn es keinen Formelbezug zu dieser Zelle gibt, wird null zurückgegeben. Weitere Details und Beispiele finden Sie unter[`GetDependentsInCalculation`](../../cell/getdependentsincalculation)

### Siehe auch

* class [Cells](../../cells)
* namensraum [Aspose.Cells](../../cells)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->