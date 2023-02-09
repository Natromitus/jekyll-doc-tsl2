---
layout: default
title: BLECharacteristicWithNamedValue
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/BLECharacteristicWithNamedValue
---
# Assert.BLECharacteristicWithNamedValue&lt;T,T1&gt; method

Creates an action that asserts that the value of a BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected.

```csharp
public static AssertBLEProperty<T, T1> BLECharacteristicWithNamedValue<T, T1>(
    GNServiceMethods propertyName, AssertType relation, string limitValueName, 
    Func<T1, T> manipulateLimitFunc = null, int limitVectorIndex = -2147483648)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| propertyName | BLE (REDACTED_COMPANY_ACRONYM) service characteristic name |
| relation | Type of relation to assert |
| limitValueName | Name of the limit value, stored in the test case context collection, to compare with |
| manipulateLimitFunc | The function to use to manipulate the limit value stored in the test case context before the compare |
| limitVectorIndex | Vector index of the value to compare with (default: NoLimitVectorIndex, means: it is not a vector!) |

## See Also

* class [AssertBLEProperty&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertBLEProperty-2Type)
* class [Assert](../AssertType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->