---
title: Application.NewFileTaskPane property (Access)
keywords: vbaac10.chm12605
f1_keywords:
- vbaac10.chm12605
ms.prod: access
api_name:
- Access.Application.NewFileTaskPane
ms.assetid: 22b069c2-9c3a-7ee1-e47f-4916a24b32d0
ms.date: 02/05/2019
ms.localizationpriority: medium
---


# Application.NewFileTaskPane property (Access)

Returns a **NewFile** object that represents a document listed on the **New File** task pane. Read-only **NewFile** object.


## Syntax

_expression_.**NewFileTaskPane**

_expression_ A variable that represents an **[Application](Access.Application.md)** object.


## Example

This example creates a file list item on the **New File** task pane in the **New from existing file** section.


```vb
Dim nftpTemp As Office.NewFile 
 
Set nftpTemp = Application.NewFileTaskPane 
 
nftpTemp.Add FileName:="C:\Sales_Quarterly.mdb", _ 
 Section:=msoNewfromExistingFile, DisplayName:="Quarterly Sales", _ 
 Action:=msoCreateNewFile
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]