---
title: MetaProperties object (Office)
keywords: vbaof11.chm274000
f1_keywords:
- vbaof11.chm274000
ms.prod: office
api_name:
- Office.MetaProperties
ms.assetid: 957a6e06-3348-b180-3655-06ffbfb69e12
ms.date: 01/18/2019
ms.localizationpriority: medium
---


# MetaProperties object (Office)

Represents a collection of properties describing the metadata stored in a document.


## Example

In the following example, a **MetaProperties** object is passed to a validation function. The function then validates the value of a single property represented by its index and returns the result.


```vb
Function ValidateMetaProperty(ByVal metaProps As MetaProperties) As String 
Dim result As String 
 
result = metaProps(1).Validate 
ValidateMetaProperty = result 
End Function
```


## See also

- [MetaProperties object members](overview/Library-Reference/metaproperties-members-office.md)
- [Object Model Reference](overview/Library-Reference/reference-object-library-reference-for-office.md)





[!include[Support and feedback](~/includes/feedback-boilerplate.md)]