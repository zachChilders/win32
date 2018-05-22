---
title: EN\_OLEOPFAILED notification code
description: Notifies a rich edit control's parent window that a user action on a Component Object Model (COM) object has failed. A rich edit control sends this notification code in the form of a WM\_NOTIFY message.
ms.assetid: 'b674c36f-2454-473e-8e1c-368c0afd8c34'
keywords: ["EN_OLEOPFAILED notification code Windows Controls"]
topic_type:
- apiref
api_name:
- EN_OLEOPFAILED
api_location:
- Richedit.h
api_type:
- HeaderDef
---

# EN\_OLEOPFAILED notification code

Notifies a rich edit control's parent window that a user action on a Component Object Model (COM) object has failed. A rich edit control sends this notification code in the form of a [**WM\_NOTIFY**](wm-notify.md) message.


```C++
EN_OLEOPFAILED

    penOleOpFailed = (ENOLEOPFAILED *) lParam; 
```



## Parameters

<dl> <dt>

*lParam* 
</dt> <dd>

An [**ENOLEOPFAILED**](enoleopfailed.md) structure that contains information about the failure.

</dd> </dl>

## Return value

This notification code returns zero.

## Remarks

The parent window will always get a [**WM\_NOTIFY**](wm-notify.md) message for this event, it does not require a notification mask sent with [**EM\_SETEVENTMASK**](em-seteventmask.md).

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Richedit.h</dt> </dl> |



## See also

<dl> <dt>

**Reference**
</dt> <dt>

[**ENOLEOPFAILED**](enoleopfailed.md)
</dt> </dl>

�

�




