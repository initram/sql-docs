---
title: "AttributeHierarchyEnabled Element (ASSL) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.technology: 
  - "analysis-services"
  - "docset-sql-devref"
ms.topic: "reference"
api_name: 
  - "AttributeHierarchyEnabled Element"
api_location: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
topic_type: 
  - "apiref"
f1_keywords: 
  - "AttributeHierarchyEnabled"
helpviewer_keywords: 
  - "AttributeHierarchyEnabled element"
ms.assetid: 1e95307f-530e-4e98-a0e1-2b0462d330a3
author: minewiskan
ms.author: owend
manager: craigg
---
# AttributeHierarchyEnabled Element (ASSL)
  Determines whether an attribute hierarchy is enabled for the attribute.  
  
## Syntax  
  
```xml  
  
<DimensionAttribute><!-- or CubeAttribute -->  
   ...  
   <AttributeHierarchyEnabled>...</AttributeHierarchyEnabled>  
   ...  
</DimensionAttribute>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|Boolean|  
|Default value|`True`|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent element|[CubeAttribute](../data-type/cubeattribute-data-type-assl.md), [DimensionAttribute](../data-type/dimensionattribute-data-type-assl.md)|  
|Child elements|None|  
  
## Remarks  
 The `AttributeHierarchyEnabled` element determines whether an attribute hierarchy is generated by [!INCLUDE[msCoName](../../../includes/msconame-md.md)] [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] [!INCLUDE[ssASnoversion](../../../includes/ssasnoversion-md.md)] for the attribute. If the attribute hierarchy is not enabled, then the attribute cannot be used in a user-defined hierarchy, nor can the attribute hierarchy be referenced in Multidimensional Expressions (MDX) statements.  
  
 The elements that correspond to the parents of `AttributeHierarchyEnabled` in the Analysis Management Objects (AMO) object model are <xref:Microsoft.AnalysisServices.CubeAttribute> and <xref:Microsoft.AnalysisServices.DimensionAttribute>.  
  
## See Also  
 [AttributeHierarchyVisible Element &#40;ASSL&#41;](visible-element-assl.md)   
 [Properties &#40;ASSL&#41;](properties-assl.md)  
  
  
