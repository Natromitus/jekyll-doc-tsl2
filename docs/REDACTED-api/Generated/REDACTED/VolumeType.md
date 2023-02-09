---
layout: default
title: Volume
grand_parent: (REDACTED_FRAMEWORK) API
parent: 0
has_children: True
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/VolumeType
---
# Volume class

Factory for volume related test actions

```csharp
public static class Volume
```

## Public Members

| name | description |
| --- | --- |
| static [DownWithButton](Volume/DownWithButton) { get; } | Factory for actions that decrease the mic and streamer volumes with HI button. |
| static [EnsureMuted](Volume/EnsureMuted) { get; } | Factory for actions that ensure that the mic and streamer are muted with HI button. |
| static [EnsureUnmuted](Volume/EnsureUnmuted) { get; } | Factory for actions that ensure that the mic and streamer are unmuted with HI button. |
| static [IsMicDefaultVolume](Volume/IsMicDefaultVolume) { get; } | Factory for actions that assert that the mic is at the default level for the active program |
| static [IsMicMuted](Volume/IsMicMuted) { get; } | Factory for actions that assert that the mic is muted for the active program |
| static [IsMicMutedWithButton](Volume/IsMicMutedWithButton) { get; } | Factory for actions that assert that the mic is muted with button for the active program |
| static [IsMicUnmuted](Volume/IsMicUnmuted) { get; } | Factory for actions that assert that the mic is unmuted for the active program |
| static [IsMicUnmutedWithButton](Volume/IsMicUnmutedWithButton) { get; } | Factory for actions that assert that the mic is unmuted with button for the active program |
| static [IsMicVolumeAboveMinimum](Volume/IsMicVolumeAboveMinimum) { get; } | Factory for actions that assert that the mic is above the minimum level for the active program |
| static [IsMicVolumeAtMaximum](Volume/IsMicVolumeAtMaximum) { get; } | Factory for actions that assert that the mic is at the maximum level for the active program |
| static [IsMicVolumeAtMinimum](Volume/IsMicVolumeAtMinimum) { get; } | Factory for actions that assert that the streamer is at the minimum level for the active program |
| static [IsMicVolumeBelowMaximum](Volume/IsMicVolumeBelowMaximum) { get; } | Factory for actions that assert that the mic is below the maximum level for the active program |
| static [IsSecondaryVolumeAboveMinimum](Volume/IsSecondaryVolumeAboveMinimum) { get; } | Factory for actions that assert that the secondary volume is above the minimum level for the active program |
| static [IsSecondaryVolumeAtDefault](Volume/IsSecondaryVolumeAtDefault) { get; } | Factory for actions that assert that the secondary volume is at the default level for the active program |
| static [IsSecondaryVolumeAtMaximum](Volume/IsSecondaryVolumeAtMaximum) { get; } | Factory for actions that assert that the secondary volume is at the maximum level for the active program |
| static [IsSecondaryVolumeAtMinimum](Volume/IsSecondaryVolumeAtMinimum) { get; } | Factory for actions that assert that the secondary volume is at the minimum level for the active program |
| static [IsSecondaryVolumeBelowMaximum](Volume/IsSecondaryVolumeBelowMaximum) { get; } | Factory for actions that assert that the secondary volume is below the maximum level for the active program |
| static [IsSecondaryVolumeMuted](Volume/IsSecondaryVolumeMuted) { get; } | Factory for actions that assert that the secondary volume is muted for the active program |
| static [IsSecondaryVolumeUnmuted](Volume/IsSecondaryVolumeUnmuted) { get; } | Factory for actions that assert that the secondary volume is unmuted for the active program |
| static [IsStreamerAboveMinimum](Volume/IsStreamerAboveMinimum) { get; } | Factory for actions that assert that the streamer volume is above the minimum level for the active program |
| static [IsStreamerAtMaximum](Volume/IsStreamerAtMaximum) { get; } | Factory for actions that assert that the streamer volume is at the maximum level for the active program |
| static [IsStreamerAtMinimum](Volume/IsStreamerAtMinimum) { get; } | Factory for actions that assert that the streamer volume is at the minimum level for the active program |
| static [IsStreamerBelowMaximum](Volume/IsStreamerBelowMaximum) { get; } | Factory for actions that assert that the streamer volume is below the maximum level for the active program |
| static [IsStreamerDefaultVolume](Volume/IsStreamerDefaultVolume) { get; } | Factory for actions that assert that the streamer is at the default level for the active program |
| static [IsStreamerMuted](Volume/IsStreamerMuted) { get; } | Factory for actions that assert that the streamer is muted for the active program |
| static [IsStreamerMutedWithButton](Volume/IsStreamerMutedWithButton) { get; } | Factory for actions that assert that the streamer is muted with button for the active program |
| static [IsStreamerUnmuted](Volume/IsStreamerUnmuted) { get; } | Factory for actions that assert that the streamer is unmuted for the active program |
| static [IsStreamerUnmutedWithButton](Volume/IsStreamerUnmutedWithButton) { get; } | Factory for actions that assert that the streamer is unmuted with button for the active program |
| static [MicMinVolumeToggle](Volume/MicMinVolumeToggle) { get; } | Creates an action that simulates a toggle of minimum mic volume (MinVolToggle) Toggles between the minimum Mic volume and the previous volume (volume before toggle to minimum) |
| static [PressButtonDown](Volume/PressButtonDown) { get; } | Creates an action that simulates a volume down button press at the HI, but does NOT wait for the volume to change. |
| static [PressButtonUp](Volume/PressButtonUp) { get; } | Creates an action that simulates a volume up button press at the HI, but does NOT wait for the volume to change. |
| static [ToggleMuteWithButton](Volume/ToggleMuteWithButton) { get; } | Factory for actions that toggles the mute state of the mic and streamer with HI button. |
| static [UpWithButton](Volume/UpWithButton) { get; } | Creates an action that increases the mic and streamer volumes with HI button. |
| static [IsMicVolume](Volume/IsMicVolume)(…) | Factory for actions that assert that the mic volume level is as expected for the active program (2 methods) |
| static [IsSecondaryVolume](Volume/IsSecondaryVolume)(…) | Factory for actions that assert that the secondary volume level is as expected for the active program (2 methods) |
| static [IsStreamerVolume](Volume/IsStreamerVolume)(…) | Factory for actions that assert that the streamer volume level is as expected for the active program (2 methods) |
| static [Mic](Volume/Mic)(…) | Factory for actions that read the mic volume for the active program and stores it in the test case context under the specified name. |
| static [Secondary](Volume/Secondary)(…) | Factory for actions that read the secondary volume for the active program and stores it in the test case context under the specified name. |
| static [Streamer](Volume/Streamer)(…) | Factory for actions that read the streamer volume for the active program and stores it in the test case context under the specified name. |

## See Also

* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskNamespace)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
