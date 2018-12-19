﻿---
title: JobManifest.ManifestAsString Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: ManifestAsString Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.JobManifest.ManifestAsString
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.jobmanifest.manifestasstring(v=VS.90)
ms:contentKeyID: 35520944
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.JobManifest.ManifestAsString
- Microsoft.Web.Media.TransformManager.JobManifest.get_ManifestAsString
- Microsoft.Web.Media.TransformManager.JobManifest.set_ManifestAsString
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.JobManifest.get_ManifestAsString
- Microsoft.Web.Media.TransformManager.JobManifest.ManifestAsString
- Microsoft.Web.Media.TransformManager.JobManifest.set_ManifestAsString
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# ManifestAsString Property

Gets the manifest XML content.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
PublicPropertyManifestAsStringAsStringGetSet
'Usage
DiminstanceAsJobManifestDimvalueAsStringvalue = instance.ManifestAsString

instance.ManifestAsString = value
```

``` csharp
publicstringManifestAsString { get; set; }
```

``` c++
public:
propertyString^ ManifestAsString {
    String^ get ();
    voidset (String^ value);
}
```

``` fsharp
memberManifestAsString : stringwithget, set
```

``` jscript
function getManifestAsString () : Stringfunction setManifestAsString (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
The manifest XML content.  

## See Also

#### Reference

[JobManifest Class](jobmanifest-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
