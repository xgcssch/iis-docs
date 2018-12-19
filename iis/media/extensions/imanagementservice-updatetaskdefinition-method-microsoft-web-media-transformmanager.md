﻿---
title: IManagementService.UpdateTaskDefinition Method  (Microsoft.Web.Media.TransformManager)
TOCTitle: UpdateTaskDefinition Method
ms:assetid: M:Microsoft.Web.Media.TransformManager.IManagementService.UpdateTaskDefinition(Microsoft.Web.Media.TransformManager.TaskDefinition)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.imanagementservice.updatetaskdefinition(v=VS.90)
ms:contentKeyID: 35520740
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.IManagementService.UpdateTaskDefinition
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.ServiceLibrary.dll
api_name:
- Microsoft.Web.Media.TransformManager.IManagementService.UpdateTaskDefinition
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# UpdateTaskDefinition Method

Adds or replaces a single task as defined in the job template.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.ServiceLibrary (in Microsoft.Web.Media.TransformManager.ServiceLibrary.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
SubUpdateTaskDefinition ( _
    taskDefinitionAsTaskDefinition _
)
'Usage
DiminstanceAsIManagementServiceDimtaskDefinitionAsTaskDefinition

instance.UpdateTaskDefinition(taskDefinition)
```

``` csharp
[OperationContractAttribute]
voidUpdateTaskDefinition(
    TaskDefinitiontaskDefinition
)
```

``` c++
[OperationContractAttribute]
voidUpdateTaskDefinition(
    TaskDefinition^ taskDefinition
)
```

``` fsharp
[<OperationContractAttribute>]
abstractUpdateTaskDefinition : 
        taskDefinition:TaskDefinition->unit
```

``` jscript
functionUpdateTaskDefinition(
    taskDefinition : TaskDefinition
)
```

#### Parameters

  - taskDefinition  
    Type: [Microsoft.Web.Media.TransformManager. . :: . .TaskDefinition](taskdefinition-class-microsoft-web-media-transformmanager.md)  
    A [TaskDefinition](taskdefinition-class-microsoft-web-media-transformmanager.md) object.  

## See Also

#### Reference

[IManagementService Interface](imanagementservice-interface-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
