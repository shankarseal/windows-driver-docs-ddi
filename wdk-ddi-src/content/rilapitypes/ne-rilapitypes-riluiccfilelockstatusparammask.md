---
UID: NE:rilapitypes.RILUICCFILELOCKSTATUSPARAMMASK
title: RILUICCFILELOCKSTATUSPARAMMASK (rilapitypes.h)
description: "Microsoft reserves the RILUICCFILELOCKSTATUSPARAMMASK enumeration for internal use only. Don't use this enumeration in your code."
old-location: netvista\riluiccfilelockstatusparammask_2.htm
tech.root: netvista
ms.date: 02/26/2018
keywords: ["RILUICCFILELOCKSTATUSPARAMMASK enumeration"]
ms.keywords: RILUICCFILELOCKSTATUSPARAMMASK, RILUICCFILELOCKSTATUSPARAMMASK enumeration [Network Drivers Starting with Windows Vista], RIL_PARAM_UFLS_ALL, RIL_PARAM_UFLS_PINREFERENCE, netvista.riluiccfilelockstatusparammask_2, rilapitypes/RILUICCFILELOCKSTATUSPARAMMASK, rilapitypes/RIL_PARAM_UFLS_ALL, rilapitypes/RIL_PARAM_UFLS_PINREFERENCE
req.header: rilapitypes.h
req.include-header: 
req.target-type: Windows
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
req.lib: NtosKrnl.exe
req.dll: 
req.irql: 
targetos: Windows
req.typenames: RILUICCFILELOCKSTATUSPARAMMASK
req.product: Windows 10 or later.
f1_keywords:
 - RILUICCFILELOCKSTATUSPARAMMASK
 - rilapitypes/RILUICCFILELOCKSTATUSPARAMMASK
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - rilapitypes.h
api_name:
 - RILUICCFILELOCKSTATUSPARAMMASK
---

# RILUICCFILELOCKSTATUSPARAMMASK enumeration (rilapitypes.h)


## -description

This topic supports the Windows driver infrastructure and is not intended to be used directly from your code.

## -enum-fields

### -field RIL_PARAM_UFLS_ACCESSCONDITION

### -field RIL_PARAM_UFLS_PINREFERENCE

### -field RIL_PARAM_UFLS_ALL

## -syntax

```cpp
typedef enum _RILUICCFILELOCKSTATUSPARAMMASK {
  RIL_PARAM_UFLS_PINREFERENCE,
  RIL_PARAM_UFLS_ALL
} RILUICCFILELOCKSTATUSPARAMMASK;
```

