---
layout: default
title: AssertCharacteristic
grand_parent: 
parent: BLE
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BLE/AssertCharacteristic
---
# BLE.AssertCharacteristic&lt;T&gt; method

Creates an action that asserts that the value of a BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected.

```csharp
public static AssertBLEProperty<T, T> AssertCharacteristic<T>(GNServiceMethods propertyName, 
    AssertType relation, T limitValue)
    where T : IComparable<T>
```

| parameter | description |
| --- | --- |
| propertyName | BLE (REDACTED_COMPANY_ACRONYM) service characteristic name |
| relation | Type of relation to assert |
| limitValue | Value to compare with |

## See Also

* class [AssertBLEProperty&lt;T,T1&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertBLEProperty-2Type)
* class [BLE](../BLEType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../BLEType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->