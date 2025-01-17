---
title: InterruptMonitor Class 
linktitle: InterruptMonitor
second_title: Aspose.Cells for Go via C++ API Reference
description: 'InterruptMonitor class. Encapsulates the object that represents interruptmonitor in Go.'
type: docs
weight: 200
url: /go-cpp/interruptmonitor/
---

## InterruptMonitor class

Represents all operator about the interrupt.

```go

type InterruptMonitor struct  {
	ptr unsafe.Pointer
}

```
## Constructors

| Method | Description |
| --- | --- |
|[NewInterruptMonitor](./newinterruptmonitor/) | Default constructor. | 

## Methods

| Method | Description |
| --- | --- |
|[IsNull](./isnull/) | Checks whether the implementation object is nullptr. | 
|[IsInterruptionRequested](./isinterruptionrequested/) | Mark the monitor as requesting interruption | 
|[Interrupt](./interrupt/) | Interrupt the current operator. | 
