﻿---
title: SheetSet
second_title: Aspose.Cells for Node.js via C++ API Reference
description: Describes a set of sheets.
type: docs
url: /nodejs-cpp/sheetset/
---

## SheetSet class

Describes a set of sheets.

```javascript
class SheetSet;
```


## Constructors

| Name | Description |
| --- | --- |
| [constructor(number[])](#constructor-numberarray-)| Creates a sheet set based on exact sheet indexes. |
| [constructor(string[])](#constructor-stringarray-)| Creates a sheet set based on exact sheet names. |

## Methods

| Method | Description |
| --- | --- |
| [isNull()](#isNull--)| Checks whether the implementation object is null. |
| static [getActive()](#getActive--)| Gets a set with active sheet of the workbook. |
| static [getVisible()](#getVisible--)| Gets a set with visible sheets of the workbook in their original order. |
| static [getAll()](#getAll--)| Gets a set with all sheets of the workbook in their original order. |


### constructor(number[]) {#constructor-numberarray-}

Creates a sheet set based on exact sheet indexes.

```javascript
constructor(sheetIndexes: number[]);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndexes | number[] | zero based sheet indexes. |

**Remarks**

If a sheet is encountered that is not in the workbook, an exception will be thrown during rendering.

### constructor(string[]) {#constructor-stringarray-}

Creates a sheet set based on exact sheet names.

```javascript
constructor(sheetNames: string[]);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetNames | string[] | sheet names. |

**Remarks**

If a sheet is encountered that is not in the workbook, an exception will be thrown during rendering.

### isNull() {#isNull--}

Checks whether the implementation object is null.

```javascript
isNull() : boolean;
```


### getActive() {#getActive--}

Gets a set with active sheet of the workbook.

```javascript
static getActive() : SheetSet;
```


**Returns**

[SheetSet](../sheetset/)

### getVisible() {#getVisible--}

Gets a set with visible sheets of the workbook in their original order.

```javascript
static getVisible() : SheetSet;
```


**Returns**

[SheetSet](../sheetset/)

### getAll() {#getAll--}

Gets a set with all sheets of the workbook in their original order.

```javascript
static getAll() : SheetSet;
```


**Returns**

[SheetSet](../sheetset/)


