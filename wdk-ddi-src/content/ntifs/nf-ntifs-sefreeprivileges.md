---
UID: NF:ntifs.SeFreePrivileges
title: SeFreePrivileges function (ntifs.h)
description: The SeFreePrivileges routine frees a privilege set returned by SeAccessCheck.
old-location: kernel\sefreeprivileges.htm
tech.root: kernel
ms.date: 04/30/2018
keywords: ["SeFreePrivileges function"]
ms.keywords: SeFreePrivileges, SeFreePrivileges routine [Kernel-Mode Driver Architecture], kernel.sefreeprivileges, ntifs/SeFreePrivileges, seref_e40724d7-f170-4dbd-89a6-2cdcdd13e87d.xml
req.header: ntifs.h
req.include-header: Ntifs.h
req.target-type: Universal
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: NtosKrnl.lib
req.dll: NtosKrnl.exe
req.irql: PASSIVE_LEVEL
targetos: Windows
req.typenames: 
f1_keywords:
 - SeFreePrivileges
 - ntifs/SeFreePrivileges
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - NtosKrnl.exe
api_name:
 - SeFreePrivileges
---

# SeFreePrivileges function


## -description

The <b>SeFreePrivileges</b> routine frees a privilege set returned by <b>SeAccessCheck</b>.

## -parameters

### -param Privileges [in]


Pointer to the privilege set to be freed.

## -remarks

For more information about security and access control, see the documentation on these topics in the Microsoft Windows SDK.

## -see-also

<a href="/previous-versions/windows/hardware/drivers/ff551860(v=vs.85)">PRIVILEGE_SET</a>



<a href="/windows-hardware/drivers/ddi/wdm/nf-wdm-seaccesscheck">SeAccessCheck</a>



<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-seappendprivileges">SeAppendPrivileges</a>



<a href="/windows-hardware/drivers/ddi/ntifs/nf-ntifs-seprivilegecheck">SePrivilegeCheck</a>
