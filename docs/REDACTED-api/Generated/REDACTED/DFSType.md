---
layout: default
title: DFS
grand_parent: (REDACTED_FRAMEWORK) API
parent: 0
has_children: True
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/DFSType
---
# DFS class

Factory class for actions related to DFS

```csharp
public static class DFS
```

## Public Members

| name | description |
| --- | --- |
| static [AssertDFSInitDuration](DFS/AssertDFSInitDuration)(…) | Creates an action that asserts whether the duration of the last performed DFS initialization matches the desired values. Performs an initialization of type Omni if one has not been performed yet |
| static [AssertInitializationWasSuccessful](DFS/AssertInitializationWasSuccessful)() | Creates an action that asserts the last DFS initialization was successful |
| static [CheckLogForShapingFilterName](DFS/CheckLogForShapingFilterName)(…) | Creates an action that checks the content of the DFS log file for a specific ShapingFilter name |
| static [ClearInitialization](DFS/ClearInitialization)() | Creates an action that clears the DFS initialization |
| static [ClearModelData](DFS/ClearModelData)(…) | Creates an action that clears the DFS model data |
| static [DumpModelData](DFS/DumpModelData)(…) | Creates an action that dumps (reads) the DFS model data into the test case context |
| static [Initialize](DFS/Initialize)(…) | Creates an action that performs a DFS initialization Also logs the start and end time into the TC context as internalInitStartTime and internalInitEndTime respectively |
| static [IsCleared](DFS/IsCleared)(…) | Creates an action which asserts that the DFS model is cleared (not representing any model) |
| static [IsDual](DFS/IsDual)(…) | Creates an action which asserts that the DFS model is of Dual type |
| static [IsOmni](DFS/IsOmni)(…) | Creates an action which asserts that the DFS model is of Omni type |
| static [IsTelecoil](DFS/IsTelecoil)(…) | Creates an action which asserts that the DFS model is of Telecoil type |
| static [IsTriple](DFS/IsTriple)(…) | Creates an action which asserts that the DFS model is of Triple type |
| static [PumpModelData](DFS/PumpModelData)(…) | Creates an action that pumps (sets) the DFS model data |
| static [PumpPresetModelData](DFS/PumpPresetModelData)(…) | Creates an action that pumps (sets) the DFS model data to the specified model |
| static [SetCompressorGainForAllPowerBands](DFS/SetCompressorGainForAllPowerBands)(…) | Creates an action that sets the compressor gain for all power bands to the chosen value |
| static [SetLinearCompressorGainForAllPowerBands](DFS/SetLinearCompressorGainForAllPowerBands)(…) | Creates an action that sets the compressor gain for all power bands to a linear curve created from the chosen value |

## See Also

* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskNamespace)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->