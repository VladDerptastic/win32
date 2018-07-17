---
Description: Starts the service.
ms.assetid: 499e4650-255f-4c84-98fc-de81d5cd6daf
title: StartService method of the Msvm\_TerminalService class
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- Msvm_TerminalService.StartService
api_type: 
- COM
api_location: 
- vmms.exe
---

# StartService method of the Msvm\_TerminalService class

Starts the service.

## Syntax


```mof
uint32 StartService();
```



## Parameters

This method has no parameters.

## Return value

This method returns one of the following values:

<dl> <dt>

**Completed with No Error** (0)
</dt> <dt>

**Not supported** (1)
</dt> </dl>

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8.1<br/>                                                                                  |
| Minimum supported server<br/> | Windows Server 2012 R2<br/>                                                                       |
| Namespace<br/>                | Root\\virtualization\\v2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



## See also

<dl> <dt>

[**Msvm\_TerminalService**](msvm-terminalservice.md)
</dt> </dl>

 

 



