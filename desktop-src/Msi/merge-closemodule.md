---
Description: The CloseModule method of the Merge object closes the currently open Windows Installer merge module.
ms.assetid: bbe8ab14-3d8e-441c-a9bf-0319a9b3a5de
title: Merge.CloseModule method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- Merge.CloseModule
- IMsmMerge.CloseModule
api_type: 
- COM
api_location: 
- Mergemod.dll
---

# Merge.CloseModule method

The **CloseModule** method of the [**Merge**](merge-object.md) object closes the currently open Windows Installer merge module.

## Syntax


```JScript
Merge.CloseModule()
```



## Parameters

This method has no parameters.

## Return value

This method does not return a value.

## Remarks

Closing a merge module will not affect any errors that have not been retrieved.

### C++

See [**CloseModule**](https://msdn.microsoft.com/en-us/library/Aa369267(v=VS.85).aspx) function.

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Version<br/> | Mergemod.dll 1.0 or later<br/>                                                    |
| Header<br/>  | <dl> <dt>Mergemod.h</dt> </dl>   |
| DLL<br/>     | <dl> <dt>Mergemod.dll</dt> </dl> |



 

 



