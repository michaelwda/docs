---
title: "remove (C# Reference)"
ms.date: 07/20/2015
f1_keywords: 
  - "remove_CSharpKeyword"
helpviewer_keywords: 
  - "remove event accessor [C#]"
ms.assetid: c8223426-c17b-4fe2-8406-01564cf1dd2b
---
# remove (C# Reference)
The `remove` contextual keyword is used to define a custom event accessor that is invoked when client code unsubscribes from your [event](../../../csharp/language-reference/keywords/event.md). If you supply a custom `remove` accessor, you must also supply an [add](../../../csharp/language-reference/keywords/add.md) accessor.  
  
## Example  
 The following example shows an event with custom [add](../../../csharp/language-reference/keywords/add.md) and `remove` accessors. For the full example, see [How to:  Implement Interface Events](../../../csharp/programming-guide/events/how-to-implement-interface-events.md).  
  
 [!code-csharp[csrefKeywordsContextual#15](../../../csharp/language-reference/keywords/codesnippet/CSharp/remove_1.cs)]  
  
 You do not typically need to provide your own custom event accessors. The accessors that are automatically generated by the compiler when you declare an event are sufficient for most scenarios.  
  
## See Also  
 [Events](../../../csharp/programming-guide/events/index.md)
