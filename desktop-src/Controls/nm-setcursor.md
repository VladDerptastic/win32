---
title: NM_SETCURSOR notification code (Commctrl.h)
description: Notifies a control's parent window that the control is setting the cursor in response to a WM\_SETCURSOR message. This notification code is sent in the form of a WM\_NOTIFY message.
ms.assetid: 8d70563f-05a3-4116-b686-6d9063940fae
keywords:
- NM_SETCURSOR notification code Windows Controls
topic_type:
- apiref
api_name:
- NM_SETCURSOR
api_location:
- Commctrl.h
api_type:
- HeaderDef
ms.topic: reference
ms.date: 05/31/2018
---

# NM\_SETCURSOR notification code

Notifies a control's parent window that the control is setting the cursor in response to a [**WM\_SETCURSOR**](https://docs.microsoft.com/windows/desktop/menurc/wm-setcursor) message. This notification code is sent in the form of a [**WM\_NOTIFY**](wm-notify.md) message.


```C++
NM_SETCURSOR

    lpnmm = (LPNMMOUSE) lParam; 
```



## Parameters

<dl> <dt>

*lParam* 
</dt> <dd>

A pointer to an [**NMMOUSE**](/windows/win32/api/commctrl/ns-commctrl-nmmouse) structure that contains additional information about this notification.

</dd> </dl>

## Return value

Return zero to enable the control to set the cursor or nonzero to prevent the control from setting the cursor.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



 

 





