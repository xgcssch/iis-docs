﻿---
title: AdaptiveSourceManager.SendExtendedCommand Method
TOCTitle: SendExtendedCommand Method
ms:assetid: eb8c0537-f09d-4e22-b557-bd4d3dccb1aa
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ822864(v=VS.90)
ms:contentKeyID: 50079618
ms.date: 11/19/2012
mtps_version: v=VS.90
dev_langs:
- csharp
- c++
- jscript
---

# AdaptiveSourceManager.SendExtendedCommand Method

**Applies to:** Windows Store apps only

Reserved for future use.

## Syntax

``` csharp
public void SendExtendedCommand(
string cmd,
string parameter
)
```

``` c++
public:
virtual void SendExtendedCommand(
[InAttribute] String^ cmd, 
[InAttribute] String^ parameter
) sealed
```

``` jscript
public final function SendExtendedCommand(
cmd : String, 
parameter : String
)
```

## Parameters

  - cmd  
    \[in\] The extended command to send.

  - parameter  
    \[in\] The parameter associated with the command.

## Return Value

If the method succeeds, it returns S\_OK. Otherwise, it returns an HRESULT error code.

## Requirements

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Minimum supported client</strong></p></td>
<td><p>Windows 8</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum supported server</strong></p></td>
<td><p>Not Supported</p></td>
</tr>
<tr class="odd">
<td><p><strong>Metadata</strong></p></td>
<td><p>Microsoft.Media.AdaptiveStreaming.winmd</p></td>
</tr>
</tbody>
</table>
