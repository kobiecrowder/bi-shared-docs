---
title: "Attributes Element (XMLA) | Microsoft Docs"
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
# Attributes Element (XMLA)

  Contains a collection of [Attribute](../xml-elements-properties/attribute-element-xmla.md) elements used by the parent [Insert](../xml-elements-commands/insert-element-xmla.md) or [Update](../xml-elements-commands/update-element-xmla.md) command, or by the parent [Where](../xml-elements-properties/where-element-xmla.md) element.  
  
## Syntax  
  
```xml  
  
<Insert > <!-- or one of the elements listed below in the Element relationships table -->  
   ...  
   <Attributes>  
      <Attribute>...</Attribute>  
   </Attributes>  
   ...  
</Insert>  
```  
  
## Element characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|None|  
|Default value|None|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Insert](../xml-elements-commands/insert-element-xmla.md), [Update](../xml-elements-commands/update-element-xmla.md), [Where](../xml-elements-properties/where-element-xmla.md)|  
|Child elements|[Attribute](../xml-elements-properties/attribute-element-xmla.md)|  
  
## Remarks  
  
