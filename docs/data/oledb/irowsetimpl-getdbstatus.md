---
title: "IRowsetImpl::GetDBStatus | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["GetDBStatus", "IRowsetImpl.GetDBStatus", "IRowsetImpl::GetDBStatus"]
dev_langs: ["C++"]
helpviewer_keywords: ["GetDBStatus method"]
ms.assetid: e51d8ee2-fc0c-4909-861c-026c94fb0dfc
caps.latest.revision: 8
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "data-storage"]
---
# IRowsetImpl::GetDBStatus
Returns the `DBSTATUS` status flags for the specified field.  
  
## Syntax  
  
```cpp
      virtual DBSTATUS GetDBStatus(RowClass* currentRow,  
   ATLCOLUMNINFO* columnNames);  
```  
  
#### Parameters  
 [in] `currentRow`  
 The current row.  
  
 [in] `columnNames`  
 The column for which status is being requested.  
  
## Return Value  
 The [DBSTATUS](https://msdn.microsoft.com/en-us/library/ms722617.aspx) flags for the column.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetImpl Class](../../data/oledb/irowsetimpl-class.md)