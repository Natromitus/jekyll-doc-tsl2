---
layout: default
title: VectorElement
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/VectorElement
---
# Assert.VectorElement&lt;T&gt; method (1 of 2)

Creates an action that finds the location (collection) of a vector HI property and asserts that the value of an individual element is within the expected limit.

```csharp
public static AssertComparable<T, T> VectorElement<T>(string propertyName, AssertType relation, 
    T limitValue, int vectorIndex, ProgramLocation program = ProgramLocation.GlobalProperties)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| propertyName | Property name |
| relation | Type of relation to assert |
| limitValue | Value to compare with |
| vectorIndex | Index of vector element to compare |
| program | The program where the property is suggested to be located (Default: GlobalProperties, means: CCOS) |

## See Also

* class [AssertComparable&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertComparable-2Type)
* enum [ProgramLocation](../ProgramLocationType)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

---

# Assert.VectorElement&lt;T&gt; method (2 of 2)

Creates an action that asserts that the value of an individual element of a vector HI property is as expected.

```csharp
public static AssertComparable<T, T> VectorElement<T>(ProgramLocation program, 
    PropertyLocation location, string propertyName, AssertType relation, T limitValue, 
    int vectorIndex)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| program | Program |
| location | Property location |
| propertyName | Property name |
| relation | Type of relation to assert |
| limitValue | Value to compare with |
| vectorIndex | Index of vector element to compare |

## See Also

* class [AssertComparable&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertComparable-2Type)
* enum [ProgramLocation](../ProgramLocationType)
* enum [PropertyLocation](../PropertyLocationType)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
