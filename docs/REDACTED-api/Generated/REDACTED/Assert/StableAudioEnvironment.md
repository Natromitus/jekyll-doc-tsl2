---
layout: default
title: StableAudioEnvironment
grand_parent: 
parent: Assert
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Assert/StableAudioEnvironment
---
# Assert.StableAudioEnvironment method

Creates an action that will wait a while for a stable audio environment

```csharp
public static WaitForStableAudioEnvironment StableAudioEnvironment(
    double speechDetectorLeftMin = 0m, double speechDetectorLeftMax = 0m, 
    double speechDetectorRightMin = 0m, double speechDetectorRightMax = 0m, 
    double noiseDetectorLeftMin = 0m, double noiseDetectorLeftMax = 0m, 
    double noiseDetectorRightMin = 0m, double noiseDetectorRightMax = 0m, 
    double quietDetectorLeftMin = 0m, double quietDetectorLeftMax = 0m, 
    double quietDetectorRightMin = 0m, double quietDetectorRightMax = 0m, 
    double rearSpeechDetectorLeftMin = 0m, double rearSpeechDetectorLeftMax = 0m, 
    double rearSpeechDetectorRightMin = 0m, double rearSpeechDetectorRightMax = 0m)
```

| parameter | description |
| --- | --- |
| speechDetectorLeftMin | Min speech probability for Speech Detector Left (default: 0.0) |
| speechDetectorLeftMax | Max speech probability for Speech Detector Left (default: 0.0) |
| speechDetectorRightMin | Min speech probability for Speech Detector Right (default: 0.0) |
| speechDetectorRightMax | Max speech probability for Speech Detector Right (default: 0.0) |
| noiseDetectorLeftMin | Min noise probability for Noise Detector Left (default: 0.0) |
| noiseDetectorLeftMax | Max noise probability for Noise Detector Left (default: 0.0) |
| noiseDetectorRightMin | Min noise probability for Noise Detector Right (default: 0.0) |
| noiseDetectorRightMax | Max noise probability for Noise Detector Right (default: 0.0) |
| quietDetectorLeftMin | Min quiet probability for Quiet Detector Left (default: 0.0) |
| quietDetectorLeftMax | Max quiet probability for Quiet Detector Left (default: 0.0) |
| quietDetectorRightMin | Min quiet probability for Quiet Detector Right (default: 0.0) |
| quietDetectorRightMax | Max quiet probability for Quiet Detector Right (default: 0.0) |
| rearSpeechDetectorLeftMin | Min speech probability for Rear Speech Detector Left (default: 0.0) |
| rearSpeechDetectorLeftMax | Max speech probability for Rear Speech Detector Left (default: 0.0) |
| rearSpeechDetectorRightMin | Min speech probability for Rear Speech Detector Right (default: 0.0) |
| rearSpeechDetectorRightMax | Max speech probability for Rear Speech Detector Right (default: 0.0) |

## See Also

* class??[WaitForStableAudioEnvironment](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioActions/WaitForStableAudioEnvironmentType)
* class??[Assert](../AssertType)
* namespace??[(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../AssertType)
* assembly??[(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
