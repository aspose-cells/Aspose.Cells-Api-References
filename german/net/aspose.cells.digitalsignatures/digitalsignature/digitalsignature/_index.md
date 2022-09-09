---
title: DigitalSignature
second_title: Aspose.Cells für .NET-API-Referenz
description: Konstrukteur von digitalSignature. Verwendet .Net-Implementierung.
type: docs
weight: 10
url: /de/net/aspose.cells.digitalsignatures/digitalsignature/digitalsignature/
---
## DigitalSignature(X509Certificate2, string, DateTime) {#constructor_1}

Konstrukteur von digitalSignature. Verwendet .Net-Implementierung.

```csharp
public DigitalSignature(X509Certificate2 certificate, string comments, DateTime signTime)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | X509Certificate2 | Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde. |
| comments | String | Der Zweck der Unterschrift. |
| signTime | DateTime | Die UTC-Zeit, zu der das Dokument signiert wurde. |

### Siehe auch

* class [DigitalSignature](../../digitalsignature)
* namensraum [Aspose.Cells.DigitalSignatures](../../digitalsignature)
* Montage [Aspose.Cells](../../../)

---

## DigitalSignature(byte[], string, string, DateTime) {#constructor}

Konstrukteur von digitalSignature. Verwendet Hüpfburg-Implementierung.

```csharp
public DigitalSignature(byte[] rawData, string password, string comments, DateTime signTime)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawData | Byte[] | Ein Byte-Array, das Daten aus einem X.509-Zertifikat enthält. |
| password | String | Das Kennwort, das für den Zugriff auf die X.509-Zertifikatsdaten erforderlich ist. |
| comments | String | Der Zweck der Unterschrift. |
| signTime | DateTime | Die UTC-Zeit, zu der das Dokument signiert wurde. |

### Siehe auch

* class [DigitalSignature](../../digitalsignature)
* namensraum [Aspose.Cells.DigitalSignatures](../../digitalsignature)
* Montage [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->