---
description: "supportsDataDefinitionAndDataManipulationTransactions Method (SQLServerDatabaseMetaData)"
title: "SupportsDataDefinitionAndDataManipulationTransactions Method | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: reference
apiname: 
  - "SQLServerDatabaseMetaData.supportsDataDefinitionAndDataManipulationTransactions"
apilocation: 
  - "sqljdbc.jar"
apitype: "Assembly"
ms.assetid: fe91c601-9bb3-4364-9131-575a94d3a1b3
author: David-Engel
ms.author: v-davidengel
---
# supportsDataDefinitionAndDataManipulationTransactions Method (SQLServerDatabaseMetaData)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Retrieves whether this database supports both data definition and data manipulation statements within a transaction.  
  
## Syntax  
  
```  
  
public boolean supportsDataDefinitionAndDataManipulationTransactions()  
```  
  
## Return Value  
 **true** if supported. Otherwise, **false**.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This suportsDataDefinitionAndDataManipulationTransactions method is specified by the suportsDataDefinitionAndDataManipulationTransactions method in the java.sql.DatabaseMetaData interface.  
  
## See Also  
 [SQLServerDatabaseMetaData Methods](../../../connect/jdbc/reference/sqlserverdatabasemetadata-methods.md)   
 [SQLServerDatabaseMetaData Members](../../../connect/jdbc/reference/sqlserverdatabasemetadata-members.md)   
 [SQLServerDatabaseMetaData Class](../../../connect/jdbc/reference/sqlserverdatabasemetadata-class.md)  
  
  
