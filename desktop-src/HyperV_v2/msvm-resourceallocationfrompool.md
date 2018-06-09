---
Description: Associates an instance of a resource allocation with the resource pool from which it is allocated.
ms.assetid: A2B3996D-7886-4B5F-BC89-EFDC1A48249B
title: Msvm\_ResourceAllocationFromPool class
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Msvm\_ResourceAllocationFromPool class

Associates an instance of a resource allocation with the resource pool from which it is allocated.

The following syntax is simplified Managed Object Format (MOF) code, and it includes all of the inherited properties.

## Syntax

``` syntax
[Association, Dynamic, Provider("VmmsWmiInstanceAndMethodProvider"), AMENDMENT]
class Msvm_ResourceAllocationFromPool : CIM_ResourceAllocationFromPool
{
  CIM_ResourcePool                  REF Antecedent;
  CIM_ResourceAllocationSettingData REF Dependent;
};
```

## Members

The **Msvm\_ResourceAllocationFromPool** class has these types of members:

-   [Properties](#properties)

### Properties

The **Msvm\_ResourceAllocationFromPool** class has these properties.

<dl> <dt>

**Antecedent**
</dt> <dd> <dl> <dt>

Data type: **[**CIM\_ResourcePool**](https://msdn.microsoft.com/library/cc136903)**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: **Override**, **Max** (1)
</dt> </dl>

The resource pool. This property is inherited from [**CIM\_ResourceAllocationFromPool**](https://msdn.microsoft.com/library/cc150673).

</dd> <dt>

**Dependent**
</dt> <dd> <dl> <dt>

Data type: **[**CIM\_ResourceAllocationSettingData**](https://msdn.microsoft.com/library/mt146214)**
</dt> <dt>

Access type: Read-only
</dt> </dl>

The resource allocation. This property is inherited from [**CIM\_ResourceAllocationFromPool**](https://msdn.microsoft.com/library/cc150673).

</dd> </dl>

## Remarks

Access to the **Msvm\_ResourceAllocationFromPool** class might be restricted by UAC Filtering. For more information, see [User Account Control and WMI](https://msdn.microsoft.com/library/aa826699).

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8 \[desktop apps only\]<br/>                                                              |
| Minimum supported server<br/> | Windows Server 2012 \[desktop apps only\]<br/>                                                    |
| Namespace<br/>                | Root\\Virtualization\\V2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



## See also

<dl> <dt>

[**CIM\_ResourceAllocationFromPool**](cim-resourceallocationfrompool.md)
</dt> <dt>

[**CIM\_ResourceAllocationFromPool**](https://msdn.microsoft.com/library/cc150673)
</dt> <dt>

[**Msvm\_ResourceAllocationFromPool (V1)**](https://msdn.microsoft.com/library/cc136876)
</dt> <dt>

[Resource Management Classes](resource-management-classes.md)
</dt> </dl>

 

 



