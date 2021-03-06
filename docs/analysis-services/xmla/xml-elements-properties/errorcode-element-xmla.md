---
title: "ErrorCode Element (XMLA) | Microsoft Docs"
description: Learn how the ErrorCode element contains the numeric return code of the parent Error element.
ms.date: 07/24/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: xmla
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# ErrorCode Element (XMLA)

  Contains the numeric return code of the parent [Error](../xml-elements-properties/error-element-xmla.md) element.  
  
## Syntax  
  
```xml  
  
<Error>  
   ...  
   <ErrorCode>...</ErrorCode>  
   ...  
</Error>  
```  
  
## Element characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|UnsignedInt|  
|Default value|None|  
|Cardinality|1-1: Required element that occurs once and only once.|  
  
## Element relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Error](../xml-elements-properties/error-element-xmla.md)|  
|Child elements|None|  
  
## Remarks  

