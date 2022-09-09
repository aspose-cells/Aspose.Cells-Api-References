---
title: Copy
second_title: Справочник по Aspose.Cells для .NET API
description: Скопируйте картинку.
type: docs
weight: 180
url: /ru/net/aspose.cells.drawing/picture/copy/
---
## Picture.Copy method

Скопируйте картинку.

```csharp
public void Copy(Picture source, CopyOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | Picture | Исходная картинка. |
| options | CopyOptions | Варианты копирования. |

### Примеры

```csharp

[C#]
//Создание экземпляра объекта Workbook
Workbook workbook = new Workbook();
Worksheet worksheet = workbook.Worksheets[0];
//вставляем первую картинку
int imgIndex1 = worksheet.Pictures.Add(1, 1, "1.png");
//Получить вставленный объект изображения
Picture pic1 = worksheet.Pictures[imgIndex1];
//вставляем вторую картинку
int imgIndex2 = worksheet.Pictures.Add(1, 9, "2.jpeg");
//Получить вставленный объект изображения
Picture pic2 = worksheet.Pictures[imgIndex2];
// Скопируйте изображение 1 в изображение 2. Вы получите два объекта изображения 1, которые накладываются друг на друга.
CopyOptions opt = new CopyOptions();
pic2.Copy(pic1, opt);
// Сохраняем файл excel.
workbook.Save("result.xlsx");
```

### Смотрите также

* class [CopyOptions](../../../aspose.cells/copyoptions)
* class [Picture](../../picture)
* пространство имен [Aspose.Cells.Drawing](../../picture)
* сборка [Aspose.Cells](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Cells.dll -->