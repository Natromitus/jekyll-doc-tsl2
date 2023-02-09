---
layout: default
title: SetCompressorGainForAllPowerBands
grand_parent: 
parent: DFS
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/DFS/SetCompressorGainForAllPowerBands
---
# DFS.SetCompressorGainForAllPowerBands method

Creates an action that sets the compressor gain for all power bands to the chosen value

```csharp
public static SetCompressorGainForAllPowerBands SetCompressorGainForAllPowerBands(
    int[] compressorGain, ProgramLocation program = ProgramLocation.Preset00)
```

| parameter | description |
| --- | --- |
| compressorGain | Compressor gain to set to all power bands |
| program | The sound program (must be PresetXX, default: Preset00) |

## See Also

* class [SetCompressorGainForAllPowerBands](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/SetCompressorGainForAllPowerBandsType)
* enum [ProgramLocation](../ProgramLocationType)
* class [DFS](../DFSType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../DFSType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->