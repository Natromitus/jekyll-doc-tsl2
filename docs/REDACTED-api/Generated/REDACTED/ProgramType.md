---
layout: default
title: Program
grand_parent: (REDACTED_FRAMEWORK) API
parent: 0
has_children: True
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ProgramType
---
# Program class

Factory class to create actions related to HI programs

```csharp
public static class Program
```

## Public Members

| name | description |
| --- | --- |
| static [CreateOnlineProgram](Program/CreateOnlineProgram) { get; } | Creates an action that will create a sound program and associate it with the [`SoundProgram`](../(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContext/SoundProgram) |
| static [HasNoWirelessStreamMixedIn](Program/HasNoWirelessStreamMixedIn) { get; } | Creates an action which asserts that the currently running program does not have a wireless stream mixed-in |
| static [HasWirelessStreamMixedIn](Program/HasWirelessStreamMixedIn) { get; } | Creates an action which asserts that the active program has a wireless stream mixed-in |
| static [IsAutoPhone](Program/IsAutoPhone) { get; } | Creates an action which checks if the active program of the HI is the auto phone program |
| static [IsBTB](Program/IsBTB) { get; } | Creates an action which checks if the active program of the HI is the BTB program |
| static [IsDfsProgram](Program/IsDfsProgram) { get; } | Creates an action which checks if the current running program is the DFS initialization program |
| static [IsInSituProgram](Program/IsInSituProgram) { get; } | Creates an action which checks if the current running program is the in-situ program |
| static [IsIPhone](Program/IsIPhone) { get; } | Creates an action which checks if the active program of the HI is the IPhone program |
| static [IsOnlineProgram](Program/IsOnlineProgram) { get; } | Creates an action which checks if the current running program is the on-line sound program |
| static [IsOsProgram](Program/IsOsProgram) { get; } | Creates an action which checks if the active program of the HI is the OS Program |
| static [IsProgram1](Program/IsProgram1) { get; } | Creates an action which checks if the active program of the HI is Program 1 |
| static [IsProgram10](Program/IsProgram10) { get; } | Creates an action which checks if the active program of the HI is Program 10 |
| static [IsProgram2](Program/IsProgram2) { get; } | Creates an action which checks if the active program of the HI is Program 2 |
| static [IsProgram3](Program/IsProgram3) { get; } | Creates an action which checks if the active program of the HI is Program 3 |
| static [IsProgram4](Program/IsProgram4) { get; } | Creates an action which checks if the active program of the HI is Program 4 |
| static [IsProgram5](Program/IsProgram5) { get; } | Creates an action which checks if the active program of the HI is Program 5 |
| static [IsProgram6](Program/IsProgram6) { get; } | Creates an action which checks if the active program of the HI is Program 6 |
| static [IsProgram7](Program/IsProgram7) { get; } | Creates an action which checks if the active program of the HI is Program 7 |
| static [IsProgram8](Program/IsProgram8) { get; } | Creates an action which checks if the active program of the HI is Program 8 |
| static [IsProgram9](Program/IsProgram9) { get; } | Creates an action which checks if the active program of the HI is Program 9 |
| static [IsSAS](Program/IsSAS) { get; } | Creates an action which checks if the active program of the HI is the streamer program |
| static [IsSASA](Program/IsSASA) { get; } | Creates an action which checks if the active program is the streamer program, using streamer channel A |
| static [IsSASB](Program/IsSASB) { get; } | Creates an action which checks if the active program is the streamer program, using streamer channel B |
| static [IsSASC](Program/IsSASC) { get; } | Creates an action which checks if the active program is the streamer program, using streamer channel C |
| static [SasChange](Program/SasChange) { get; } | Creates an action that triggers a SAS change event to the OS |
| static [SasChangeExpectingNoShift](Program/SasChangeExpectingNoShift) { get; } | Creates an action that triggers a SAS change event to the OS, but expecting it to not shift program |
| static [Shift](Program/Shift) { get; } | Creates an action that triggers a program shift event to the OS |
| static [ShiftExpectingNoShift](Program/ShiftExpectingNoShift) { get; } | Creates an action that triggers a program shift event to the OS, but expecting it to not shift program |
| static [ShiftNoWaitForMelodyDone](Program/ShiftNoWaitForMelodyDone) { get; } | Creates an action that triggers a program shift event to the OS, but will not wait for any melody played to end (usable when the melody is expected to repeat) |
| static [SwitchToIphone](Program/SwitchToIphone) { get; } | Creates an action that triggers an enter IPhone program event to the OS |
| static [IsProgram](Program/IsProgram)(…) | Creates an action which checks if the current program of the HI is the expected |
| static [SetInputMode](Program/SetInputMode)(…) | Creates an action that can set the input mode of a program. |
| static [SetLinearGain](Program/SetLinearGain)(…) | Creates an action that sets the requested property to the requested linear gain for all power bands (2 methods) |
| static [Start](Program/Start)(…) | Creates an action that starts the requested program in the HI |
| static [StartPresetWithAllBBRecipies](Program/StartPresetWithAllBBRecipies)(…) | Creates an action that can start a preset with all its Blackboard recipes |
| static [Synchronize](Program/Synchronize)(…) | Creates an action that synchronizes the requested program in the HI |

## See Also

* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskNamespace)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
