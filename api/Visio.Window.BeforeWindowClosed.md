---
title: Window.BeforeWindowClosed event (Visio)
keywords: vis_sdr.chm11619075
f1_keywords:
- vis_sdr.chm11619075
ms.prod: visio
api_name:
- Visio.Window.BeforeWindowClosed
ms.assetid: 4543e237-6b2c-d02c-66df-9f90b0266e4b
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# Window.BeforeWindowClosed event (Visio)

Occurs before a window is closed.


## Syntax

_expression_.**BeforeWindowClosed** (_Window_)

_expression_ A variable that represents a **[Window](Visio.Window.md)** object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Window_|Required| **[IVWINDOW]**|The window that is going to be closed.|

## Remarks

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own **Event** objects, use the **[Add](visio.eventlist.add.md)** or **[AddAdvise](visio.eventlist.addadvise.md)** method. 

To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. 

To create an **Event** object that receives notification, use the **AddAdvise** method. 

To find an event code for the event that you want to create, see [Event codes](../visio/Concepts/event-codesvisio.md).

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]