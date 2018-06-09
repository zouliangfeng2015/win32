---
Description: Gets or sets a value that represents the month component of the datetime value.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 05818f0a-7e15-4ddd-a6a7-9d16ae82cd3c
ms.prod: windows-server-dev
ms.technology: windows-management-instrumentation
ms.tgt_platform: multiple
title: SWbemDateTime.Month property
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# SWbemDateTime.Month property

The **Month** property of the [**SWbemDateTime**](swbemdatetime.md) object gets or sets a value that represents the month component of the datetime value. The number must be in the range of 01 through 12 or the error **wbemValueOutOfRange** is returned.

For an explanation of this syntax, see [Document Conventions for the Scripting API](document-conventions-for-the-scripting-api.md).

This property is read/write.

## Syntax


```VB
SWbemDateTime.Month As Long
```



## Property value

## Examples

For examples of using the [**SWbemDateTime**](swbemdatetime.md) object to convert CIM [**DATETIME**](datetime.md) values to and from either the **FILETIME** format or the **VT\_DATE** format, see [WMI Tasks: Dates and Times](wmi-tasks--dates-and-times.md). For a description of the CIM **DATETIME** format, see [Date and Time Format](date-and-time-format.md).

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Header<br/>                   | <dl> <dt>Wbemdisp.h</dt> </dl>   |
| Type library<br/>             | <dl> <dt>Wbemdisp.tlb</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Wbemdisp.dll</dt> </dl> |
| CLSID<br/>                    | CLSID\_SWbemDateTime<br/>                                                         |
| IID<br/>                      | IID\_ISWbemDateTime<br/>                                                          |



## See also

<dl> <dt>

[**SWbemDateTime.MonthSpecified**](swbemdatetime-monthspecified.md)
</dt> <dt>

[**SWbemDateTime**](swbemdatetime.md)
</dt> <dt>

[DATETIME](datetime.md)
</dt> </dl>

 

 



