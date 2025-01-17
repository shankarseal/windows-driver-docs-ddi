---
UID: NC:d3dkmthk.PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE
title: PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE
description: Outputs duplicate of a handle to a hardware queue.
tech.root: display
ms.date: 04/04/2019
keywords: ["PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE callback function"]
req.header: d3dkmthk.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 1903
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
ms.custom: DXGKDDI_INTERFACE_VERSION_WDDM2_6, 19H1
f1_keywords:
 - PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE
 - d3dkmthk/PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - d3dkmthk.h
api_name:
 - PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE
product:
 - Windows
dev_langs:
 - c++
---

# PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE callback function


## -description

Outputs duplicate of a handle to a hardware queue.

## -parameters

### -param unnamedParam1

Pointer to a [D3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE](ns-d3dkmthk-_d3dkmt_outputduplpresenttohwqueue.md) structure.

## -returns

Return STATUS_SUCCESS if the operation succeeds.

## -prototype

```
//Declaration

PFND3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE Pfnd3dkmtOutputduplpresenttohwqueue; 

// Definition

NTSTATUS Pfnd3dkmtOutputduplpresenttohwqueue 
(
	const D3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE *
)
{...}

```

## -remarks

## -see-also

