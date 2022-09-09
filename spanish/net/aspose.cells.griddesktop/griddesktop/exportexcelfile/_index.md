---
title: ExportExcelFile
second_title: Referencia de API de Aspose.Cells para .NET
description: Exporta a un archivo de Excel.
type: docs
weight: 690
url: /es/net/aspose.cells.griddesktop/griddesktop/exportexcelfile/
---
## ExportExcelFile(string) {#exportexcelfile_2}

Exporta a un archivo de Excel.

```csharp
public void ExportExcelFile(string fileName)
```

### Ejemplos

```csharp
[C#]
private void button1_Click(object sender, System.EventArgs e)
{
	gridDesktop1.Worksheets.ExportExcelFile("savedemo.xls");
}

[Visual Basic]
Private Sub menuItem1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles menuItem7.Click
	gridDesktop1.Worksheets.ExportExcelFile("savedemo.xls")
End Sub

```

### Ver también

* class [GridDesktop](../../griddesktop)
* espacio de nombres [Aspose.Cells.GridDesktop](../../griddesktop)
* asamblea [Aspose.Cells.GridDesktop](../../../)

---

## ExportExcelFile(string, FileFormatType) {#exportexcelfile_3}

Exporta a un archivo de Excel.

```csharp
public void ExportExcelFile(string fileName, FileFormatType fileFormatType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileName | String | El nombre del archivo creado. |
| fileFormatType | FileFormatType | Tipo de formato de archivo de Excel. |

### Ver también

* enum [FileFormatType](../../fileformattype)
* class [GridDesktop](../../griddesktop)
* espacio de nombres [Aspose.Cells.GridDesktop](../../griddesktop)
* asamblea [Aspose.Cells.GridDesktop](../../../)

---

## ExportExcelFile(Stream) {#exportexcelfile}

Exporta a un flujo de archivo de Excel, incluido el flujo de E/S de disco o el flujo de memoria.

```csharp
public void ExportExcelFile(Stream stream)
```

### Ejemplos

```csharp
[C#]
private void button1_Click(object sender, System.EventArgs e)
{
	FileStream fs = new FileStream("d:\\bookx.xls", FileMode.OpenOrCreate);
	try
	{
		gridDesktop1.Worksheets.ExportExcelFile(fs);
	}
	catch(Exception ex)
	{
	}
	finally
	{
		fs.Close();
	}
}

[Visual Basic]
Private Sub menuItem1_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles menuItem6.Click
	Dim fs As FileStream =  New FileStream("d:\bookx.xls", FileMode.OpenOrCreate)
	Try
		gridDesktop1.Worksheets.ExportExcelFile(fs)
	Catch ex As Exception
		Throw ex
	Finally
		fs.Close()
	End Try
End Sub

```

### Ver también

* class [GridDesktop](../../griddesktop)
* espacio de nombres [Aspose.Cells.GridDesktop](../../griddesktop)
* asamblea [Aspose.Cells.GridDesktop](../../../)

---

## ExportExcelFile(Stream, FileFormatType) {#exportexcelfile_1}

Exporta a un flujo de archivo de Excel, incluido el flujo de E/S de disco o el flujo de memoria.

```csharp
public void ExportExcelFile(Stream stream, FileFormatType fileFormatType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Transmitir dónde guardar la hoja de cálculo. |
| fileFormatType | FileFormatType | Tipo de formato de archivo de Excel. |

### Ver también

* enum [FileFormatType](../../fileformattype)
* class [GridDesktop](../../griddesktop)
* espacio de nombres [Aspose.Cells.GridDesktop](../../griddesktop)
* asamblea [Aspose.Cells.GridDesktop](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.GridDesktop.dll -->