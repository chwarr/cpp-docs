---
title: "RuntimeClass::GetRuntimeClassName Method | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["implements/Microsoft::WRL::RuntimeClass::GetRuntimeClassName"]
dev_langs: ["C++"]
helpviewer_keywords: ["GetRuntimeClassName method"]
ms.assetid: f6388163-fe65-4948-a4bc-ae6826f480e7
caps.latest.revision: 4
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "uwp"]
---
# RuntimeClass::GetRuntimeClassName Method

Gets the runtime class name of the current RuntimeClass object.

## Syntax

```cpp
STDMETHOD( GetRuntimeClassName )(
    _Out_ HSTRING* runtimeName
);
```

### Parameters

*runtimeName*  
When this operation completes, the runtime class name.

## Return Value

S_OK if successful; otherwise, an HRESULT that indicates the error.

## Remarks

An assert error is emitted if &#95;&#95;WRL_STRICT&#95;&#95; or &#95;&#95;WRL_FORCE_INSPECTABLE_CLASS_MACRO&#95;&#95; isn't defined.

## Requirements

**Header:** implements.h

**Namespace:** Microsoft::WRL

## See Also

[RuntimeClass Class](../windows/runtimeclass-class.md)