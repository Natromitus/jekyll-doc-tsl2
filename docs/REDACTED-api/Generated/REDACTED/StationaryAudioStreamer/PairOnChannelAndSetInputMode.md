---
layout: default
title: PairOnChannelAndSetInputMode
grand_parent: 
parent: StationaryAudioStreamer
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/StationaryAudioStreamer/PairOnChannelAndSetInputMode
---
# StationaryAudioStreamer.PairOnChannelAndSetInputMode method

Creates an action that will pair the hearing instrument with an accessory to streamer channel A, B and C (if applicable), if a AccessoryType is provided that cannot be paired via SAS channel, that parameter will be ignored.

```csharp
public static TestActionBase<HearingInstrumentContext> PairOnChannelAndSetInputMode(
    StreamerChannel channel = StreamerChannel.ChannelA, 
    InputModeId inputMode = InputModeId.ExternalStreamingMic1)
```

| parameter | description |
| --- | --- |
| channel | Channel to pair the SAS on (Default is Channel A) |
| inputMode | Input Mode (Default: ExternalStreamingMic1) |

## See Also

* class [HearingInstrumentContext](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextType)
* enum [StreamerChannel](../StreamerChannelType)
* enum [InputModeId](../InputModeIdType)
* class [StationaryAudioStreamer](../StationaryAudioStreamerType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../StationaryAudioStreamerType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->