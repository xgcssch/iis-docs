﻿---
title: QuickStartGroup.Id Property  (Microsoft.Web.PlatformInstaller)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Web.PlatformInstaller.QuickStartGroup.Id
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.platforminstaller.quickstartgroup.id(v=VS.90)
ms:contentKeyID: 22187112
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.PlatformInstaller.QuickStartGroup.Id
- Microsoft.Web.PlatformInstaller.QuickStartGroup.get_Id
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.PlatformInstaller.dll
api_name:
- Microsoft.Web.PlatformInstaller.QuickStartGroup.get_Id
- Microsoft.Web.PlatformInstaller.QuickStartGroup.Id
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# Id Property

Gets or sets the unique identifier of the quick start group.

**Namespace:**  [Microsoft.Web.PlatformInstaller](microsoft-web-platforminstaller-namespace.md)  
**Assembly:**  Microsoft.Web.PlatformInstaller (in Microsoft.Web.PlatformInstaller.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyIdAsStringGet
'Usage
DiminstanceAsQuickStartGroupDimvalueAsStringvalue = instance.Id
```

``` csharp
publicstringId { get; }
```

``` c++
public:
propertyString^ Id {
    String^ get ();
}
```

``` jscript
function getId () : String
```

#### Property Value

Type: String  
A string that contains the unique identifier of the quick start group.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see <https://msdn.microsoft.com/en-us/library/8skskf63(v=vs.90)>.

## See Also

#### Reference

[QuickStartGroup Class](quickstartgroup-class-microsoft-web-platforminstaller.md)

[QuickStartGroup Members](quickstartgroup-members-microsoft-web-platforminstaller.md)

[Microsoft.Web.PlatformInstaller Namespace](microsoft-web-platforminstaller-namespace.md)
