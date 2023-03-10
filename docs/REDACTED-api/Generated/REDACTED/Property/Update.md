---
layout: default
title: Update
grand_parent: 
parent: Property
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Property/Update
---
# Property.Update&lt;T&gt; method

Factory for actions that update the value of a HI property

```csharp
public static UpdateProperty<T> Update<T>(string propertyName, Func<T, T> updateFunction, 
    FinalProgramming finalProgrammingAfter = FinalProgramming.No, 
    ProgramLocation program = ProgramLocation.GlobalProperties, 
    PropertyLocation location = PropertyLocation.PropertyWillBeFound)
```

| parameter | description |
| --- | --- |
| propertyName | Property name |
| updateFunction | Function to transform current entry value into desired value |
| finalProgrammingAfter | Whether or not the device will be final programmed after updating the value (Default: FinalProgramming.No) |
| program | The program where the property is located (Default: ProgramLocation.GlobalProperties, means CCOS here) |
| location | The location (collection) where the property is located (Default: PropertyLocation.PropertyWillBeFound, property searched for in all locations) |

## See Also

* class [UpdateProperty&lt;T&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/UpdateProperty-1Type)
* enum [FinalProgramming](../FinalProgrammingType)
* enum [ProgramLocation](../ProgramLocationType)
* enum [PropertyLocation](../PropertyLocationType)
* class [Property](../PropertyType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../PropertyType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
