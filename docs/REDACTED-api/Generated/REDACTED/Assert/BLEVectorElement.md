---
layout: default
title: BLEVectorElement
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/BLEVectorElement
---
# Assert.BLEVectorElement&lt;T&gt; method

Creates an action that asserts that the value of an individual element of a vector type BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected.

```csharp
public static AssertBLEProperty<T, T> BLEVectorElement<T>(GNServiceMethods propertyName, 
    AssertType relation, T limitValue, int vectorIndex)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| propertyName | BLE (REDACTED_COMPANY_ACRONYM) service characteristic name |
| relation | Type of relation to assert |
| limitValue | Expected (equals) / undesired (not equals) value |
| vectorIndex | Index of vector element to compare |

## See Also

* class [AssertBLEProperty&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertBLEProperty-2Type)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
