---
layout: default
title: SetLinearGain
grand_parent: 
parent: Program
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Program/SetLinearGain
---
# Program.SetLinearGain method (1 of 2)

Creates an action that sets the requested property to the requested linear gain for all power bands

```csharp
public static SetLinearGainAction SetLinearGain(ProgramLocation program, PropertyLocation property, 
    string name, double value)
```

## See Also

* class [SetLinearGainAction](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions/SetLinearGainActionType)
* enum [ProgramLocation](../ProgramLocationType)
* enum [PropertyLocation](../PropertyLocationType)
* class [Program](../ProgramType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ProgramType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

---

# Program.SetLinearGain method (2 of 2)

Creates an action that sets the requested property to the requested linear gain for each of the power bands

```csharp
public static SetLinearGainAction SetLinearGain(ProgramLocation program, PropertyLocation property, 
    string name, IEnumerable<double> values)
```

## See Also

* class [SetLinearGainAction](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions/SetLinearGainActionType)
* enum [ProgramLocation](../ProgramLocationType)
* enum [PropertyLocation](../PropertyLocationType)
* class [Program](../ProgramType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ProgramType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
