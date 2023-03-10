---
layout: default
title: AllNamedVectorElements
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/AllNamedVectorElements
---
# Assert.AllNamedVectorElements&lt;T&gt; method

Creates an action that asserts that all elements in a named vector (stored in context) satisfy a condition

```csharp
public static AssertVectorElements<T> AllNamedVectorElements<T>(string valueName, 
    AssertType assertType, T limitValue, double tolerance = 0m, 
    Func<T, T> manipulateContextElementsFunc = null)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| valueName | Name of value in TC context |
| assertType | Assert type, non-numerical types can only do equality comparisons |
| limitValue | Limit value |
| tolerance | Tolerance for numerical equality comparisons (Default: 0) |
| manipulateContextElementsFunc | Function delegate invoked on each element in the vector saved in the TC context |

## See Also

* class [AssertVectorElements&lt;T&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertVectorElements-1Type)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
