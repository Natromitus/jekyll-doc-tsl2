---
layout: default
title: TriggerPairOnChannel
grand_parent: 
parent: StationaryAudioStreamer
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/StationaryAudioStreamer/TriggerPairOnChannel
---
# StationaryAudioStreamer.TriggerPairOnChannel method

Creates an action that attempts to pair the hearing instrument with an accessory to streamer channel A, B and C (if applicable), but does not perform a boot on the HI, as this might be initiated from another test action.

```csharp
public static TestActionBase<HearingInstrumentContext> TriggerPairOnChannel(
    StreamerChannel channel = StreamerChannel.ChannelA)
```

| parameter | description |
| --- | --- |
| channel | Channel to pair the SAS on (Default is Channel A) |

## See Also

* class [HearingInstrumentContext](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextType)
* enum [StreamerChannel](../StreamerChannelType)
* class [StationaryAudioStreamer](../StationaryAudioStreamerType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../StationaryAudioStreamerType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->