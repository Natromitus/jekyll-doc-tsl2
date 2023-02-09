---
layout: default
title: BluetoothBridge
grand_parent: (REDACTED_FRAMEWORK) API
parent: 0
has_children: True
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BluetoothBridgeType
---
# BluetoothBridge class

Simulated operations against the BTB2

```csharp
public static class BluetoothBridge
```

## Public Members

| name | description |
| --- | --- |
| static [ActivatePhone](BluetoothBridge/ActivatePhone) { get; } | Creates an action that simulates an activate BTB phone event to the OS, expecting a program shift |
| static [ActivatePhoneExpectingNoProgramShift](BluetoothBridge/ActivatePhoneExpectingNoProgramShift) { get; } | Creates an action that simulates an activate BTB phone event to the OS, expecting no program shift |
| static [DoubleTapCallButton](BluetoothBridge/DoubleTapCallButton) { get; } | Creates an action that triggers a double tap call button event at a BTB2, expecting a program shift |
| static [DoubleTapCallButtonExpectingNoProgramShift](BluetoothBridge/DoubleTapCallButtonExpectingNoProgramShift) { get; } | Creates an action that triggers a double tap call button event at a BTB2, expecting no program shift |
| static [HangUpPhone](BluetoothBridge/HangUpPhone) { get; } | Creates an action that simulates a hang up BTB phone event to the OS, expecting a program shift |
| static [HangUpPhoneExpectingNoProgramShift](BluetoothBridge/HangUpPhoneExpectingNoProgramShift) { get; } | Creates an action that simulates a hang up BTB phone event to the OS, expecting no program shift |
| static [LongPushCallButton](BluetoothBridge/LongPushCallButton) { get; } | Creates an action that triggers a long push call button event at a BTB2, expecting a program shift |
| static [LongPushCallButtonExpectingNoProgramShift](BluetoothBridge/LongPushCallButtonExpectingNoProgramShift) { get; } | Creates an action that triggers a long push call button event at a BTB2, expecting no program shift |
| static [Mute](BluetoothBridge/Mute) { get; } | Creates an action that triggers a press on the mute button event at a BTB2. |
| static [PairUsingProximity](BluetoothBridge/PairUsingProximity) { get; } | Creates an action that triggers a press on the proximity pairing button event at a BTB2 and attempts to actually pair it with Hearing Instrument(s). |
| static [ProgramShift](BluetoothBridge/ProgramShift) { get; } | Creates an action that triggers a press on the program button event at a BTB2. |
| static [ProgramShiftExpectingNoShift](BluetoothBridge/ProgramShiftExpectingNoShift) { get; } | Creates an action that triggers a press on the program button event at a BTB2, expecting no program shift. |
| static [StartStreaming](BluetoothBridge/StartStreaming) { get; } | Creates an action that simulates a start BTB streaming event to the OS, expecting a program shift |
| static [StartStreamingExpectingNoProgramShift](BluetoothBridge/StartStreamingExpectingNoProgramShift) { get; } | Creates an action that simulates a start BTB streaming event to the OS, expecting no program shift |
| static [TapCallButton](BluetoothBridge/TapCallButton) { get; } | Creates an action that triggers a tap call button event at a BTB2, expecting a program shift |
| static [TapCallButtonExpectingNoProgramShift](BluetoothBridge/TapCallButtonExpectingNoProgramShift) { get; } | Creates an action that triggers a tap call button event at a BTB2, expecting no program shift |
| static [TriggerPairUsingBluetooth](BluetoothBridge/TriggerPairUsingBluetooth) { get; } | Creates an action that triggers a press on the Bluetooth pairing button event at a BTB2, but do not perform any attempt to pair. |
| static [TriggerPairUsingProximity](BluetoothBridge/TriggerPairUsingProximity) { get; } | Creates an action that triggers a press on the proximity pairing button event at a BTB2, but do not perform a boot on the HI, as this might be initiated from another test action. |
| static [VolumeDown](BluetoothBridge/VolumeDown) { get; } | Creates an action that triggers a press on the volume down button event at a BTB2. |
| static [VolumeUp](BluetoothBridge/VolumeUp) { get; } | Creates an action that triggers a press on the volume up button event at a BTB2. |

## See Also

* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskNamespace)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->