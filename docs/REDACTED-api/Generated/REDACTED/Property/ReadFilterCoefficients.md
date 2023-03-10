---
layout: default
title: ReadFilterCoefficients
grand_parent: 
parent: Property
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Property/ReadFilterCoefficients
---
# Property.ReadFilterCoefficients method

Factory for actions that that reads and converts the filter coefficients at the given property into the test case context collection

```csharp
public static ReadFilterCoefficients ReadFilterCoefficients(string propertyName, 
    ProgramLocation program = ProgramLocation.GlobalProperties, 
    PropertyLocation location = PropertyLocation.PropertyWillBeFound, string valueName = "value")
```

| parameter | description |
| --- | --- |
| propertyName | Property name |
| program | The program where the property is located (Default: ProgramLocation.GlobalProperties, means CCOS here) |
| location | The location (collection) where the property is located (Default: PropertyLocation.PropertyWillBeFound, property searched for in all locations) |
| valueName | &gt;The name (default: value) to use when storing the read value in the test case context collection |

## See Also

* class [ReadFilterCoefficients](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/ReadFilterCoefficientsType)
* enum [ProgramLocation](../ProgramLocationType)
* enum [PropertyLocation](../PropertyLocationType)
* class [Property](../PropertyType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../PropertyType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
