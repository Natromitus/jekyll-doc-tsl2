---
layout: default
title: Vector
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/Vector
---
# Assert.Vector&lt;T&gt; method (1 of 2)

Creates an action that finds the location (collection) of a vector property, and asserts that the value is within the expected limit.

```csharp
public static AssertVector<T, T> Vector<T>(string propertyName, AssertType relation, 
    IList<T> limitValue, ProgramLocation program = ProgramLocation.GlobalProperties)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| propertyName | Property name |
| relation | Type of relation to assert |
| limitValue | Expected (equals) / undesired (not equals) value |
| program | The program where the property is suggested to be located (Default: GlobalProperties, means: CCOS) |

## See Also

* class [AssertVector&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertVector-2Type)
* enum [ProgramLocation](../ProgramLocationType)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

---

# Assert.Vector&lt;T&gt; method (2 of 2)

Creates an action that asserts that the value of a vector property is as expected.

```csharp
public static AssertVector<T, T> Vector<T>(ProgramLocation program, PropertyLocation location, 
    string propertyName, AssertType relation, IList<T> limitValue)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| program | Program |
| location | Property location |
| propertyName | Property name |
| relation | Type of relation to assert |
| limitValue | Expected (equals) / undesired (not equals) value |

## See Also

* class [AssertVector&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertVector-2Type)
* enum [ProgramLocation](../ProgramLocationType)
* enum [PropertyLocation](../PropertyLocationType)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
