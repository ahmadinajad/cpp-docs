---
title: "max (STL/CLR) | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-cli"]
ms.topic: "reference"
f1_keywords: ["cliext::max"]
dev_langs: ["C++"]
helpviewer_keywords: ["max function [STL/CLR]"]
ms.assetid: bf51aedc-b7a0-4b6c-a76e-fdbc4af042fa
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "dotnet"]
---
# max (STL/CLR)
Compares two objects and returns the larger of the two, where the ordering criterion may be specified by a binary predicate.  
  
## Syntax  
  
```  
template<class _Ty> inline  
    const _Ty max(const _Ty% _Left, const _Ty% _Right);  
template<class _Ty, class _Pr> inline  
    const _Ty max(const _Ty% _Left, const _Ty% _Right, _Pr _Pred);  
```  
  
## Remarks  
 This function behaves the same as the C++ Standard Library function `max`. For more information, see [max](../standard-library/algorithm-functions.md#max).  
  
## Requirements  
 **Header:** \<cliext/algorithm>  
  
 **Namespace:** cliext  
  
## See Also  
 [algorithm (STL/CLR)](../dotnet/algorithm-stl-clr.md)