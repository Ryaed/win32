---
title: JET_BKLOGTIME.Equals method (JET_BKLOGTIME)
TOCTitle: Equals method (JET_BKLOGTIME)
ms:assetid: M:Microsoft.Isam.Esent.Interop.JET_BKLOGTIME.Equals(Microsoft.Isam.Esent.Interop.JET_BKLOGTIME)
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.jet_bklogtime.equals(v=EXCHG.10)
ms:contentKeyID: 39516064
ms.date: 07/30/2014
ms.topic: reference
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.JET_BKLOGTIME.Equals
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET_BKLOGTIME.Equals method (JET_BKLOGTIME)

Returns a value indicating whether this instance is equal to another instance.

**Namespace:**  [Microsoft.Isam.Esent.Interop](./microsoft.isam.esent.interop-namespace.md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As JET_BKLOGTIME _
) As Boolean
'Usage
Dim instance As JET_BKLOGTIME
Dim other As JET_BKLOGTIME
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    JET_BKLOGTIME other
)
```

#### Parameters

  - other  
    Type: [Microsoft.Isam.Esent.Interop.JET_BKLOGTIME](./jet-bklogtime-structure2.md)  
    
    An instance to compare with this instance.

#### Return value

Type: [System.Boolean](/dotnet/api/system.boolean)  
True if the two instances are equal.  

#### Implements

[IEquatable\<T\>.Equals(T)](/dotnet/api/system.iequatable-1.equals#System_IEquatable_1_Equals__0_)  

## See also

#### Reference

[JET_BKLOGTIME structure](./jet-bklogtime-structure2.md)

[JET_BKLOGTIME members](./jet-bklogtime-members.md)

[Equals overload](./jet-bklogtime.equals-method.md)

[Microsoft.Isam.Esent.Interop namespace](./microsoft.isam.esent.interop-namespace.md)