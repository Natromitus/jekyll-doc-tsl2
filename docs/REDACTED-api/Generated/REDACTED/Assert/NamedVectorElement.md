---
layout: default
title: NamedVectorElement
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/NamedVectorElement
---
# Assert.NamedVectorElement&lt;T&gt; method

Creates an action that asserts that an individual element of a vector type stored in the test case context is as expected.

```csharp
public static AssertComparable<T, T> NamedVectorElement<T>(string name, AssertType relation, 
    T limitValue, int vectorIndex)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| name | Name of the value in the test case context |
| relation | Type of relation to assert |
| limitValue | Value to compare with |
| vectorIndex | Index of vector element to compare |

## See Also

* class [AssertComparable&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertComparable-2Type)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->