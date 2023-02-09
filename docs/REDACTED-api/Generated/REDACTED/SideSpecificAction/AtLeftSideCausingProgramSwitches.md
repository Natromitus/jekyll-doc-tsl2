---
layout: default
title: AtLeftSideCausingProgramSwitches
grand_parent: 
parent: SideSpecificAction
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/SideSpecificAction/AtLeftSideCausingProgramSwitches
---
# SideSpecificAction.AtLeftSideCausingProgramSwitches method

Creates an AggregateSideSpecificTestAction, containing a left side action and the assert actions, which will verify that each HI switch to an individually specified program.

```csharp
public static SideSpecificActions AtLeftSideCausingProgramSwitches(
    TestActionBase<HearingInstrumentContext> testAction, 
    ProgramLocationToAssert resultingProgramLeft, ProgramLocationToAssert resultingProgramRight)
```

| parameter | description |
| --- | --- |
| testAction | The action to perform at the left side HI |
| resultingProgramLeft | The program, which the left side HI must switch to |
| resultingProgramRight | The program, which the right side HI must switch to |

## See Also

* class [SideSpecificActions](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).GenericActions/SideSpecificActionsType)
* class [HearingInstrumentContext](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextType)
* enum [ProgramLocationToAssert](../ProgramLocationToAssertType)
* class [SideSpecificAction](../SideSpecificActionType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../SideSpecificActionType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->