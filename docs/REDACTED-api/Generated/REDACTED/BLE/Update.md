---
layout: default
title: Update
grand_parent: 
parent: BLE
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BLE/Update
---
# BLE.Update method (1 of 2)

Creates an action that updates the value of a (REDACTED_COMPANY_ACRONYM) Service characteristic

```csharp
public static UpdateCharacteristic Update(GNServiceMethods gnCharacteristic, 
    Func<byte[], byte[]> updateFunction, 
    FinalProgramming finalProgrammingAfter = FinalProgramming.No)
```

| parameter | description |
| --- | --- |
| gnCharacteristic | The name of the (REDACTED_COMPANY_ACRONYM) characteristic to update the value of |
| updateFunction | Function to transform current entry value into desired value |
| finalProgrammingAfter | Whether or not the device will be final programmed after updating the value (Default: FinalProgramming.No) |

## See Also

* class [UpdateCharacteristic](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/UpdateCharacteristicType)
* enum [FinalProgramming](../FinalProgrammingType)
* class [BLE](../BLEType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../BLEType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

---

# BLE.Update method (2 of 2)

Creates an action that updates the value of a BLE characteristic

```csharp
public static UpdateCharacteristic Update(ServiceCharacteristic characteristic, 
    Func<byte[], byte[]> updateFunction, 
    FinalProgramming finalProgrammingAfter = FinalProgramming.No)
```

| parameter | description |
| --- | --- |
| characteristic | The characteristic to update the value of |
| updateFunction | Function to transform current entry value into desired value |
| finalProgrammingAfter | Whether or not the device will be final programmed after updating the value (Default: FinalProgramming.No) |

## See Also

* class [UpdateCharacteristic](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/UpdateCharacteristicType)
* struct [ServiceCharacteristic](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).Types/ServiceCharacteristicType)
* enum [FinalProgramming](../FinalProgrammingType)
* class [BLE](../BLEType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../BLEType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
