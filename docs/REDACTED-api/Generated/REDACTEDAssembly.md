---
layout: default
title: (REDACTED).(REDACTED_OTHER_FRAMEWORK)
grand_parent: 
parent: (REDACTED_FRAMEWORK) API
has_children: True
permalink: /(REDACTED_FRAMEWORK)-api/ReSoundSETTestwareTestCaseActionsRatatoskAssembly
---
# (REDACTED).(REDACTED_OTHER_FRAMEWORK) assembly

## (REDACTED).(REDACTED_OTHER_FRAMEWORK) namespace

| public type | description |
| --- | --- |
| enum [AccessoryClass](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AccessoryClassType) | Define what class of accessory the specifyc type is |
| static class [AccessoryTypeExtensions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AccessoryTypeExtensionsType) | Extension methods to add methods to AccessoryType types. |
| static class [Assert](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AssertType) | Static class for creating actions that asserts that a HI property value is as expected |
| [Flags] enum [AudioSource](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AudioSourceType) | Audio source |
| static class [AutoPhone](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AutoPhoneType) | A factory for actions that can enable/disable the AutoPhone preset and activate/deactivate the GMR sensor. |
| static class [AutoSteering](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AutoSteeringType) | Factory class to create actions related to auto steering |
| enum [AutoSteeringStrategy](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/AutoSteeringStrategyType) | Auto steering strategies |
| static class [Blackboard](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BlackboardType) | A factory for actions that can interact with the blackboard |
| static class [BLE](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BLEType) | Factory for Bluetooth Low Energy (BLE)-related actions |
| enum [BLEProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BLEProgramType) | Locations that defines where a program is associated, according to the BLE interface. |
| static class [BluetoothBridge](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BluetoothBridgeType) | Simulated operations against the BTB2 |
| static class [Boot](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BootType) | Factory for actions booting a channel, associated to a HearingInstrumentContext, into different modes |
| enum [CalibrationType](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/CalibrationTypeType) | DFS calibration type |
| enum [ChangedBy](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ChangedByType) | Initiator of the change |
| enum [ChangeType](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ChangeTypeType) | Type of volume change |
| static class [Command](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/CommandType) | Factory for classes that can execute HI commands. |
| static class [Comment](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/CommentType) | Factory class for creating comment action |
| static class [Compressor](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/CompressorType) | A factory for compressor actions. |
| static class [Conditional](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ConditionalType) | Factory for custom conditional actions |
| static class [Custom](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/CustomType) | Factory for custom actions |
| static class [Dai](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/DaiType) | A factory for actions that can enable/disable the AutoDAI preset and activate/deactivate the DAI sensor. |
| static class [Database](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/DatabaseType) | A factory for database actions. |
| static class [DFS](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/DFSType) | Factory class for actions related to DFS |
| enum [FinalProgramming](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/FinalProgrammingType) | Perform final programming before or after booting the HI |
| static class [FmmCalibration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/FmmCalibrationType) | Factory class for FMM calibration actions |
| static class [GattEntry](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/GattEntryType) | A factory for actions that can set/read a GATT database entry value. |
| static class [HearingInstrument](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/HearingInstrumentType) | Factory class for actions related to the hearing instrument |
| enum [InputModeId](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/InputModeIdType) | Input Modes |
| enum [LogFileGeneration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/LogFileGenerationType) | Log file generation |
| static class [MediaPlayer](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/MediaPlayerType) | A factory for actions that use MediaPlayer to stream audio to device. |
| static class [Melody](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/MelodyType) | Factory class for melody player actions |
| enum [MelodyId](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/MelodyIdType) | Enum representing melody id values |
| enum [MemorySpace](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/MemorySpaceType) | Memory space type |
| static class [MirrorService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/MirrorServiceType) | Test actions to work with Mirror Service |
| enum [ModelType](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ModelTypeType) | DFS model type |
| enum [MuteState](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/MuteStateType) | Mute state |
| static class [Pair](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/PairType) | Factory class for actions related to paring of the hearing instrument |
| static class [PairingTable](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/PairingTableType) | Factory class for actions related to the paring table of the hearing instrument |
| enum [Platform](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/PlatformType) | HI platform |
| static class [Program](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ProgramType) | Factory class to create actions related to HI programs |
| enum [ProgramLocation](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ProgramLocationType) | Locations that defines where a program is associated, when setting property values (i.e. when indexing programs, i.e. NOT using the symbol for the GATT preset). |
| static class [ProgramLocationExtensions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ProgramLocationExtensionsType) | Extension methods to add methods to [`ProgramLocation`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ProgramLocationType) types. |
| enum [ProgramLocationToAssert](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/ProgramLocationToAssertType) | Locations that defines where a program is associated, when asserting the expected program is active (i.e when reading the symbol for the GATT preset). |
| static class [Property](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/PropertyType) | A factory for actions that can set/read a HI property value. |
| enum [PropertyLocation](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/PropertyLocationType) | Locations that defines in which collection a property is member |
| class [Recording](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/RecordingType) | Factory for actions that use recording, must be used in the Audio Environment |
| enum [RegisterSpace](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/RegisterSpaceType) | Register space type |
| static class [RemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/RemoteControlType) | Factory for actions that trigger an event at a Remote Control |
| [Flags] enum [RemoteControlSide](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/RemoteControlSideType) | Side that defines the selected tide on a remote control |
| static class [Repeat](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/RepeatType) | Factory for an action, which repeats other actions |
| static class [SideSpecificAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/SideSpecificActionType) | Factory for common combinations of side specific test actions/asserts |
| static class [SoundDetector](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/SoundDetectorType) | Test actions against sound detectors |
| enum [SoundType](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/SoundTypeType) | Sound type |
| static class [StandardFeatures](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/StandardFeaturesType) | Factory for Standard Features related actions |
| static class [StationaryAudioStreamer](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/StationaryAudioStreamerType) | Simulated operations against the SAS3 |
| static class [StorageLayout](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/StorageLayoutType) | A factory for actions that can set/read a storage layout property value. |
| enum [StreamerChannel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/StreamerChannelType) | Streamer channels. |
| static class [Unpair](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/UnpairType) | Factory class for actions related to unparing the hearing instrument from different elements |
| static class [Volume](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/VolumeType) | Factory for volume related test actions |
| enum [VolumeAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/VolumeActionType) | Enumeration representing volume action |
| static class [WaitFor](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/WaitForType) | Factory for wait actions |
| delegate [WaitForDeviceActionDelegate](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/WaitForDeviceActionDelegateType) | Delegate signature for the method that will determine which method is the correct for waiting |
| delegate [WaitForDeviceActionWithParameterDelegate](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/WaitForDeviceActionWithParameterDelegateType) | Delegate signature for the method that will determine which method is the correct for waiting |
| delegate [WaitForDevicesActionDelegate](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/WaitForDevicesActionDelegateType) | Delegate signature for the method that will determine which method is the correct for waiting |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Accessories namespace

| public type | description |
| --- | --- |
| static class [BluetoothBridgeFunctions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Accessories/BluetoothBridgeFunctionsType) | Common functionality related to the BluetoothBridge |
| static class [RemoteControlFunctions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Accessories/RemoteControlFunctionsType) | Collection of internal helper functions related to the Remote Control |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.CalibrationActions namespace

| public type | description |
| --- | --- |
| class [CalibrationActiveSet&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.CalibrationActions/CalibrationActiveSet-1Type) | Action that active sets property using calibration |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.GenericActions namespace

| public type | description |
| --- | --- |
| class [ConditionalResult](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.GenericActions/ConditionalResultType) | Action that conditionally checks the result of the execution of an action. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.StorageLayoutActions namespace

| public type | description |
| --- | --- |
| class [SetStandardFeatureProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.StorageLayoutActions/SetStandardFeaturePropertyType) | Action that sets the value of a StandardFeature property of the BLE (REDACTED_COMPANY_ACRONYM) service characteristic GNAllStdFeatures for the given program |
| class [SetStorageLayoutPropertyToNamedValue&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Actions.StorageLayoutActions/SetStorageLayoutPropertyToNamedValue-1Type) | Action that sets the value of a Storage Layout property and commits it to NVRAM. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions namespace

| public type | description |
| --- | --- |
| class [AssertActionFails](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertActionFailsType) | Action that asserts that execution of a specified action fails as expected. |
| class [AssertBLEProperty&lt;T,T1&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertBLEProperty-2Type) | Action that asserts that the value of a BLE (REDACTED_COMPANY_ACRONYM) service characteristic or a single element of a vector-type characteristic is within the expected limit. |
| class [AssertBLEVector&lt;T,T1&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertBLEVector-2Type) | Action that asserts that a vector type BLE (REDACTED_COMPANY_ACRONYM) service characteristic has the expected value. |
| class [AssertComparable&lt;T,T1&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertComparable-2Type) | Action that asserts that the value of a property or a single element of a vector-type property is within the expected limit. |
| class [AssertDouble](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertDoubleType) | Action that asserts that a property of type double or a single element of a vector of doubles-type property is within the expected limit. |
| class [AssertDoubleVector](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertDoubleVectorType) | Action that asserts that a vector of doubles property has the expected value. |
| class [AssertFilterCoefficients](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertFilterCoefficientsType) | Action that asserts that filter coefficients have the expected values. |
| class [AssertNull](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertNullType) | Action that asserts that the chosen property is or isn't null |
| class [AssertSFix24FilterCoefficients](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertSFix24FilterCoefficientsType) | Action that asserts that filter coefficients of type vector of hex numbers in SFix24 format have the expected values. |
| class [AssertShortVectorWithTolerance&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertShortVectorWithTolerance-1Type) | Action that asserts that a vector of shorts property has the expected value. |
| class [AssertShortWithTolerance&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertShortWithTolerance-1Type) | Action that asserts that a property of type short or a single element of a vector of shorts-type property is within the expected limit. |
| class [AssertVector&lt;T,T1&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertVector-2Type) | Action that asserts that a vector property has the expected value. |
| class [AssertVectorElements&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertVectorElements-1Type) | Action that asserts that all/any elements in a vector satisfy a condition |
| class [AssertVectorLength](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AssertActions/AssertVectorLengthType) | Action that asserts that the length of a vector matches the desired value |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioActions namespace

| public type | description |
| --- | --- |
| class [AdjustVolumeForDesiredSmoothBroadBandPower](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioActions/AdjustVolumeForDesiredSmoothBroadBandPowerType) | Action that adjusts volume for desired smooth broad band power |
| class [PlayAudio](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioActions/PlayAudioType) | Action that plays audio to device at adjusted input power for set time and optionally executes action(s) in between the streaming of the audio |
| class [WaitForStableAudioEnvironment](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioActions/WaitForStableAudioEnvironmentType) | An action that waits a while for a stable sound environment |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioRelatedActions namespace

| public type | description |
| --- | --- |
| class [VerifyInputPowerPreset1](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AudioRelatedActions/VerifyInputPowerPreset1Type) | Action that verifies Input Power Preset1 according to time audio was streamed to device and tolerance |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).AutoPhoneActions namespace

| public type | description |
| --- | --- |
| class [AutoPhoneActivation](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AutoPhoneActions/AutoPhoneActivationType) | An action that triggers activation/deactivation of the GMR sensor. |
| class [EnableAutoPhonePreset](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AutoPhoneActions/EnableAutoPhonePresetType) | An action that enables/disables the AutoPhone preset. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).AutoSteeringActions namespace

| public type | description |
| --- | --- |
| class [AssertAutoSteeringStrategy](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).AutoSteeringActions/AssertAutoSteeringStrategyType) | An action that asserts that the auto steering strategy is as expected. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BlackboardActions namespace

| public type | description |
| --- | --- |
| class [InjectRecipes](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BlackboardActions/InjectRecipesType) | An action that will inject recipes onto the blackboard of the provided program |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions namespace

| public type | description |
| --- | --- |
| class [AdvertisedData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AdvertisedDataType) | An action that collects advertised ADV_IND and SCN_RSP data from the currently connected HI. |
| class [AssertCharacteristicReadWriteNotifyConfiguration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertCharacteristicReadWriteNotifyConfigurationType) | An action that asserts that a BLE service characteristic is readable/writable and can be notified or not. |
| class [AssertCorrespondingLEAGNCharacteristicsReadWriteNotifyConfiguration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertCorrespondingLEAGNCharacteristicsReadWriteNotifyConfigurationType) | An action that asserts that the corresponding BLE Audio (LEA) and (REDACTED_COMPANY_ACRONYM) service characteristics have the correct Read/Write/Notify properties. |
| class [AssertHISecurityCapabilities](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertHISecurityCapabilitiesType) | An action that reads the security capabilities of the HI |
| class [AssertIsDiscoverableDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertIsDiscoverableDeviceType) | An action that asserts that the specified device is discoverable via BLE. |
| class [AssertIsDiscoverableService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertIsDiscoverableServiceType) | An action that asserts that the specified BLE service is discoverable. |
| class [AssertIsNotConnected](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertIsNotConnectedType) | An action that asserts that the HI is not connected via BLE. |
| class [AssertIsServiceAdvertised](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertIsServiceAdvertisedType) | An action that asserts if the specified service is advertised in the collected advertised ADV_IND and SCN_RSP data |
| class [AssertNotified](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertNotifiedType) | An action that asserts that a BLE service characteristic received a notification. |
| class [AssertNotPairedCharacteristicLength](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertNotPairedCharacteristicLengthType) | An action that asserts that not paired BLE service characteristics have the expected length. |
| class [AssertPairedCharacteristicLength](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/AssertPairedCharacteristicLengthType) | An action that asserts that paired BLE service characteristics are only accessible after authentication and that they have the expected length. |
| class [BootAndScan](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/BootAndScanType) | An action that triggers a boot of the HI into offline (not in host) mode, then a wireless scan via BLE for HIs. |
| class [ConnectToBTAddress](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/ConnectToBTAddressType) | An action that tries to connect via BLE to a HI with Bluetooth address |
| class [ConnectToName](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/ConnectToNameType) | An action that tries to connect via BLE to a HI with a device name |
| class [Disconnect](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/DisconnectType) | An action that disconnects a BLE connection against an HI |
| class [DiscoverServices](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/DiscoverServicesType) | An action that discovers BLE services, other than the (REDACTED_COMPANY_ACRONYM) service |
| class [GetCharacteristic](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/GetCharacteristicType) | An action that reads a BLE service characteristic |
| class [GetNotification](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/GetNotificationType) | An action that reads the last received BLE service notification |
| class [GNAssertSetNotifiesLEA](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/GNAssertSetNotifiesLEAType) | An action that asserts that setting a BLE (REDACTED_COMPANY_ACRONYM) service characteristic notifies a LEA service characteristic. |
| class [LEAAssertSetNotifiesGN](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/LEAAssertSetNotifiesGNType) | An action that asserts that setting a BLE Audio (LEA) service characteristic notifies a (REDACTED_COMPANY_ACRONYM) service characteristic. |
| class [NegotiateMaxMTU](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/NegotiateMaxMTUType) | An action that negotiates the Maximum MTU size via BLE |
| class [PerformBonding](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/PerformBondingType) | An action that tries to perform bonding with the connected device |
| class [SetCharacteristic](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/SetCharacteristicType) | Action that sets the value of a BLE service characteristic. |
| class [SubscribeNotification](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/SubscribeNotificationType) | An action that subscribes for a BLE service characteristic notification. |
| class [UpdateCharacteristic](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/UpdateCharacteristicType) | An action that updates the value of a BLE service characteristic |
| class [WirelessScan](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/WirelessScanType) | An action that triggers a wireless scan via BLE for HIs |
| class [WirelessScanSetDeviceName](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions/WirelessScanSetDeviceNameType) | An action that triggers a wireless scan via BLE for HIs |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.FittingService namespace

| public type | description |
| --- | --- |
| class [Event](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.FittingService/EventType) | Action that sets the value of a BLE fitting service event. |
| class [ShiftProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.FittingService/ShiftProgramType) | Action that changes the program (preset) via BLE fitting service event. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.GNService namespace

| public type | description |
| --- | --- |
| class [GNAuthenticate](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.GNService/GNAuthenticateType) | An action that tries to authenticate via BLE (REDACTED_COMPANY_ACRONYM) service |
| class [GNDiscoverCharacteristics](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.GNService/GNDiscoverCharacteristicsType) | An action that discovers BLE (REDACTED_COMPANY_ACRONYM) specific characteristics |
| class [GNSetAndCheckAllWithAuthentication](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.GNService/GNSetAndCheckAllWithAuthenticationType) | Action that sets and verifies the update of all (REDACTED_COMPANY_ACRONYM) specific characteristics, which require authentication. |
| class [GNSetAndCheckAllWithoutAuthentication](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEActions.GNService/GNSetAndCheckAllWithoutAuthenticationType) | Action that sets and verifies the update of all (REDACTED_COMPANY_ACRONYM) specific characteristics, which do not require authentication. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices namespace

| public type | description |
| --- | --- |
| static class [ASHAService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/ASHAServiceType) | Defines the available characteristics of the ASHA Service |
| class [BLEASHAService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEASHAServiceType) | Enables test actions requiring BLE ASHA service communication against a single HI |
| class [BLEAudioService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEAudioServiceType) | Enables test actions requiring BLE Audio (LEA) service communication against a single HI |
| class [BLEDevInfoService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEDevInfoServiceType) | Enables test actions requiring BLE DEVINFO (Device Information) service communication against a single HI |
| class [BLEDFUService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEDFUServiceType) | Enables test actions requiring BLE DFU (Device Firmware Update) service communication against a single HI |
| class [BLEFittingService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEFittingServiceType) | Enables test actions requiring BLE Fitting service communication against a single HI |
| class [BLEGAPService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEGAPServiceType) | Enables test actions requiring BLE GAP service communication against a single HI |
| class [BLEGATTService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEGATTServiceType) | Enables test actions requiring BLE GATT service communication against a single HI |
| class [BLEGNService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEGNServiceType) | Enables test actions requiring BLE (REDACTED_COMPANY_ACRONYM) (Great Nordic) service communication against a single HI |
| class [BLEHDIService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEHDIServiceType) | Enables test actions requiring BLE HDI (Hybrid Device Image) service (or Service Mode) communication against a single HI |
| class [BLELoLAService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLELoLAServiceType) | Enables test actions requiring BLE LoLA (Low Level Access) service communication against a single HI |
| class [BLEMFIAuthenticationService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEMFIAuthenticationServiceType) | Enables test actions requiring BLE MFI AUTH (Made For Iphone Authentication) service communication against a single HI |
| class [BLEServicesBase](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BLEServicesBaseType) | Enables test actions requiring BLE service communication against a single HI |
| class [BluetoothLowEnergy](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/BluetoothLowEnergyType) | Enables test actions requiring BLE communication against a single HI |
| static class [DevInfoService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/DevInfoServiceType) | Defines the available characteristics of the DevInfo Service |
| static class [DFUService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/DFUServiceType) | DFU Service (ONLY ACCESSIBLE IN DFU MODE!) |
| static class [FITService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/FITServiceType) | Defines the available characteristics of the BLE Fitting Service |
| static class [GAPService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/GAPServiceType) | Defines the available characteristics of the GAP Service |
| static class [GNService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/GNServiceType) | Defines the available characteristics of the (REDACTED_COMPANY_ACRONYM) Service |
| static class [LEAService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/LEAServiceType) | Defines the available characteristics of the LEA Service |
| static class [MFIService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BLEServices/MFIServiceType) | Defines the available characteristics of the MFI Service |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions namespace

| public type | description |
| --- | --- |
| class [ActivateBtbPhoneEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/ActivateBtbPhoneEventType) | An action that triggers an activate/hang up BTB phone event to the OS |
| class [ActivateBtbStreamingEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/ActivateBtbStreamingEventType) | An action that triggers a start BTB streaming event to the OS |
| class [BluetoothPairButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/BluetoothPairButtonEventAtBtb2Type) | An action that triggers a press BlueTooth pairing button event at the BTB2 |
| class [DoubleTapCallButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/DoubleTapCallButtonEventAtBtb2Type) | An action that triggers a double tap on call button event at the BTB2 |
| class [LongPushCallButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/LongPushCallButtonEventAtBtb2Type) | An action that triggers a long push on call button event at the BTB2 |
| class [MuteButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/MuteButtonEventAtBtb2Type) | An action that triggers a press mute button event at the BTB2 |
| class [ProgramButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/ProgramButtonEventAtBtb2Type) | An action that triggers a press program button event at the BTB2 |
| class [ProximityPairButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/ProximityPairButtonEventAtBtb2Type) | An action that triggers a press proximity pairing button event at the BTB2 and waits for the pairing to succeed |
| class [TapCallButtonEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/TapCallButtonEventAtBtb2Type) | An action that triggers a tap on call button event at the BTB2 |
| class [VolumeChangeEventAtBtb2](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BluetoothBridgeEventActions/VolumeChangeEventAtBtb2Type) | An action that triggers a 'volume change' event at the BTB2 |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).BootActions namespace

| public type | description |
| --- | --- |
| class [AssertBootIndicator](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BootActions/AssertBootIndicatorType) | An action that asserts that the boot indicator is as expected |
| class [BootChannel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BootActions/BootChannelType) | Action that will boot the channel based on the specified boot type |
| class [BootFlightStableDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BootActions/BootFlightStableDeviceType) | Action that will restart the device 3 times, to boot it into Flight mode and wait for the device to reach a stable state |
| class [BootNotHostStableDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BootActions/BootNotHostStableDeviceType) | Action that will boot the device into NotHostMode and wait for the device to reach a stable state |
| class [LeaveFlightEnterNotHostStableDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).BootActions/LeaveFlightEnterNotHostStableDeviceType) | This is a workaround to prevent HI from ending up with 'Cant write to bootIndicator'. Action that will restart the device, to leave Flight mode, then boot the device into NotHostMode and wait for the device to reach a stable state |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).CalibrationActions namespace

| public type | description |
| --- | --- |
| class [BaseCalibrationTrySet](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CalibrationActions/BaseCalibrationTrySetType) | Action that attempts to set the chosen property of the active calibration set and then resets the value. If value is not possible to set, throws a PropertyValidationException. |
| class [CalibrationProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CalibrationActions/CalibrationPropertyType) | A property of the active calibration set |
| class [ReadCalibrationProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CalibrationActions/ReadCalibrationPropertyType) | Action that reads the property of the current active calibration |
| class [ResetCalibration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CalibrationActions/ResetCalibrationType) | Action that resets the current active calibration to the value saved in the test case context. To be used after setting a calibration property without auto reset |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions namespace

| public type | description |
| --- | --- |
| class [CommandOffline](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/CommandOfflineType) | Action that executes an offline (i.e. require no channel) HI program (incl. OS) command and store any return value in the test case context collection under the provided name. |
| class [CommandOnline](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/CommandOnlineType) | Action that executes an online (i.e. require a channel) HI program (incl. OS) command and stores any return value in the test case context collection under the provided name. |
| class [ReadFromMemory](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/ReadFromMemoryType) | Action that reads from the memory space through Channel. |
| class [ReadFromRegister&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/ReadFromRegister-1Type) | Action that reads from the register space through Channel. |
| class [WriteToMemory&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/WriteToMemory-1Type) | Action that writes to the memory space through Channel. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Common namespace

| public type | description |
| --- | --- |
| static class [CommonFunctions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Common/CommonFunctionsType) | Collection of internal helper functions |
| static class [ProgramFunctions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Common/ProgramFunctionsType) | Collection of internal helper functions related to HI programs |
| static class [VolumeFunctions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Common/VolumeFunctionsType) | Collection of internal helper functions related to HI program volumes |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).CompareWrappers namespace

| public type | description |
| --- | --- |
| class [CompareableCurve](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompareWrappers/CompareableCurveType) | Comparer instance that are able to compare two Curve objects. |
| class [CompareableCurveArray](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompareWrappers/CompareableCurveArrayType) | Comparer instance that are able to compare two IList objects. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions namespace

| public type | description |
| --- | --- |
| class [AssertLinearGainAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions/AssertLinearGainActionType) | Action to assert a gain curve property have linear gain values |
| class [SetLinearCompressorGainCurves](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions/SetLinearCompressorGainCurvesType) | Action that sets the gain of a program to a linear level |
| class [SetLinearGainAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions/SetLinearGainActionType) | Action to set a gain curve property to a linear gain value |
| class [SetSatisfyCurrentCompressorGain](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).CompressorActions/SetSatisfyCurrentCompressorGainType) | Action that calls SetCurrentCompressorGain command which recalculates the initial gain based on target/current gain and progress with the program and linear level |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Constants namespace

| public type | description |
| --- | --- |
| static class [CalibrationConstants](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Constants/CalibrationConstantsType) | Static class containing string constants common in test cases relating to Calibration and device setup |
| static class [DFSConstants](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Constants/DFSConstantsType) | Static class containing string constants common in DFS test cases |
| static class [TimeOutConstants](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Constants/TimeOutConstantsType) | Static class containing predefined timeout values to use with (REDACTED_OTHER_FRAMEWORK). All times are in milliseconds |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DaiActions namespace

| public type | description |
| --- | --- |
| class [DaiActivation](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DaiActions/DaiActivationType) | An action to trigger activation/deactivation of the DAI sensor |
| class [EnableAutoDai](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DaiActions/EnableAutoDaiType) | An action that configures a HI to have AutoDAI preset enabled/disabled |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DataContainers namespace

| public type | description |
| --- | --- |
| class [SetAndCheck&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataContainers/SetAndCheck-1Type) | Container class to use in the common scenario where you want to set a value and expect the result to be one of the three outcomes - the same value - another value - an exception |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions namespace

| public type | description |
| --- | --- |
| class [DataLoggingBleWriteDataToDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingBleWriteDataToDeviceType) | An action that writes the DataLogging data to device over BLE. |
| class [DataLoggingExportDataFromRam](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingExportDataFromRamType) | An action that exports the DataLogging data from RAM. |
| class [DataLoggingLegacyWriteDataToDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingLegacyWriteDataToDeviceType) | An action that writes the DataLogging data to device (legacy). |
| class [DataLoggingReadData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingReadDataType) | An action that reads the DataLogging data. |
| class [DataLoggingReloadData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingReloadDataType) | An action that reloads the DataLogging data. |
| class [DataLoggingReloadSatisfy](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingReloadSatisfyType) | An action that reloads the DataLogging Satisfy data. |
| class [DataLoggingResetBatteryRelatedData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingResetBatteryRelatedDataType) | An action that resets the battery related DataLogging data. |
| class [DataLoggingResetData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingResetDataType) | An action that resets the DataLogging data. |
| class [DataLoggingResetProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingResetPropertyType) | An action that resets the DataLogging property. |
| class [DataLoggingWriteDataToDevice](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DataLoggingCommandActions/DataLoggingWriteDataToDeviceType) | An action that writes the data to device. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts namespace

| public type | description |
| --- | --- |
| class [HearingInstrumentContext](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextType) | A specialized version of a device context that represents a hearing instrument |
| static class [HearingInstrumentContextExtensions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextExtensionsType) | Extension methods to add methods to [`HearingInstrumentContext`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextType) types (and collections thereof). |
| static class [TestCaseContextExtensions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/TestCaseContextExtensionsType) | Extension methods to add methods to TestCaseContext types. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceSets namespace

| public type | description |
| --- | --- |
| class [HearingInstrumentPair&lt;TTestVector&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceSets/HearingInstrumentPair-1Type) | Container to handle a pair of hearing instruments with test vectors of type *TTestVector* |
| class [HearingInstrumentPair](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceSets/HearingInstrumentPairType) | Container to handle a pair of hearing instruments with no test vectors |
| abstract class [HearingInstrumentSet&lt;TTestVector&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceSets/HearingInstrumentSet-1Type) | Base class for hearing instrument device sets |
| class [SingleHearingInstrument&lt;TTestVector&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceSets/SingleHearingInstrument-1Type) | This class represent a single hearing instrument with test vectors of type *TTestVector* |
| class [SingleHearingInstrument](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceSets/SingleHearingInstrumentType) | This class represent a single hearing instrument with no test vectors |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions namespace

| public type | description |
| --- | --- |
| class [AssertDFSInitDuration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/AssertDFSInitDurationType) | Action that asserts whether the duration of the last performed DFS initialization matches the desired values. Performs an initialization of type Omni if one has not been performed yet |
| class [AssertDFSModelType](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/AssertDFSModelTypeType) | Action that asserts that the DFS model type is the expected. |
| class [CheckLogForText](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/CheckLogForTextType) | Action that checks the content of the DFS log file for a specific substring |
| class [CheckMaxStableGain](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/CheckMaxStableGainType) | Action that checks if the MaximumStableGain curve is equal to the chosen type |
| class [ClearInit](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/ClearInitType) | Action that clears the DFS initialization |
| class [DFSInit](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/DFSInitType) | Action that performs a DFS initialization |
| class [DumpDFSModelData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/DumpDFSModelDataType) | Action that dumps (reads) the DFS model data into the test case context |
| class [GetMaxStableGainPoint](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/GetMaxStableGainPointType) | Action that reads the high/low point of the MaximumStableGain curve and saves it into the test case context |
| class [PumpDFSModelData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/PumpDFSModelDataType) | Action that pumps (sets) DFS model data |
| class [SetCompressorGainForAllPowerBands](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DFSActions/SetCompressorGainForAllPowerBandsType) | Action that sets the compressor gain for all power bands to the chosen value |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).DirectionalityActions namespace

| public type | description |
| --- | --- |
| class [EnableRearSpeechDetector](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DirectionalityActions/EnableRearSpeechDetectorType) | An action that enables/disables the rear speech detector |
| class [ReadSoundDetectorProbability](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DirectionalityActions/ReadSoundDetectorProbabilityType) | An action that reads the probability from a single sound detector |
| class [SimulateRearSpeechDetection](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DirectionalityActions/SimulateRearSpeechDetectionType) | An action that simulates rear speech detection |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Enums namespace

| public type | description |
| --- | --- |
| static class [BLEProgramExtension](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Enums/BLEProgramExtensionType) | Extension methods to add methods to [`BLEProgram`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BLEProgramType) types. |
| enum [FITEvents](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Enums/FITEventsType) | Available fitting service events |
| enum [FITPresets](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Enums/FITPresetsType) | Available fitting service event presets |
| enum [Services](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Enums/ServicesType) | Available services |
| enum [StandardFeature](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Enums/StandardFeatureType) | Standard Feature |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Extensions namespace

| public type | description |
| --- | --- |
| static class [RatatoskExtensions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Extensions/RatatoskExtensionsType) | Extensions for the (REDACTED_OTHER_FRAMEWORK) class |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Factories namespace

| public type | description |
| --- | --- |
| static class [Aggregate](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Factories/AggregateType) | Factory for aggregated test actions |
| static class [FlightMode](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Factories/FlightModeType) | A factory for actions that triggers entering flight mode. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Features namespace

| public type | description |
| --- | --- |
| static class [Afgc](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/AfgcType) | Access to the Afgc feature properties |
| static class [AfxDfs](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/AfxDfsType) | Access to the AfxDfs feature properties |
| static class [AfxdfsInitFree](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/AfxdfsInitFreeType) | Access to the AfxdfsInitFree feature properties |
| static class [Calibration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/CalibrationType) | Contains factories related to the active calibration and its properties |
| static class [Compressor](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/CompressorType) | Access to the Compressor feature properties |
| static class [DataLogging](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/DataLoggingType) | Access to the DataLogging feature properties |
| static class [DfsInitialisation](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/DfsInitialisationType) | Access to the DfsInitialisation feature properties |
| class [DfsInitialisationBlackBoardFeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/DfsInitialisationBlackBoardFeatureProperty-1Type) | A specialized version if the [`FeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) class for properties that is associated with the DFS Initialization program and can exist on each of the sound program instances |
| class [DfsInitialisationFeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/DfsInitialisationFeatureProperty-1Type) | A specialized version of the [`FeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) class for properties that are associated with the DfsInitialisation program |
| abstract class [FeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) | Factory class to create read and set actions for a specific a interface property |
| static class [FineTuner](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FineTunerType) | Access to the FineTuner feature properties |
| static class [FittingBlockHandler](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FittingBlockHandlerType) | Access to the FittingBlockHandler feature commands |
| static class [HighFrequencyShifter](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/HighFrequencyShifterType) | Access to the HighFrequencyShifter properties |
| static class [MaxStableGain](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/MaxStableGainType) | Factory class for actions related to the MaximumStableGain curve |
| static class [MelodyPlayer](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/MelodyPlayerType) | Access to the Melody Player feature properties |
| class [OsBlackBoardFeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/OsBlackBoardFeatureProperty-1Type) | A specialized version of the [`FeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) class for blackboard properties that are associated with the OS (GlobalProperties) program |
| class [OsFeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/OsFeatureProperty-1Type) | A specialized version of the [`FeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) class for properties that are associated with the OS (GlobalProperties) program |
| static class [Pds](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/PdsType) | Access to the PDS feature properties |
| static class [Satisfy](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SatisfyType) | Access to the Satisfy feature properties |
| class [SoundProgramBlackBoardFeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SoundProgramBlackBoardFeatureProperty-1Type) | A specialized version if the [`FeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) class for properties that is associated with the sound program and can exist on each of the sound program instances |
| class [SoundProgramCurveArrayProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SoundProgramCurveArrayPropertyType) | Factory class to create read and set actions for a specific a interface property of type Curve array |
| class [SoundProgramFeatureProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SoundProgramFeatureProperty-1Type) | A specialized version if the [`FeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/FeatureProperty-1Type) class for properties that is associated with the sound program and can exist on each of the sound program instances |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).FlightModeActions namespace

| public type | description |
| --- | --- |
| class [EnterFlightMode](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).FlightModeActions/EnterFlightModeType) | An action that triggers entering flight mode. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).FmmCalibrationActions namespace

| public type | description |
| --- | --- |
| class [AssertFmmCalibration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).FmmCalibrationActions/AssertFmmCalibrationType) | Action that asserts that FMM calibration data exists in the device |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).GenericActions namespace

| public type | description |
| --- | --- |
| class [RepeatActionWithAssertProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).GenericActions/RepeatActionWithAssertProgramType) | Repeats an action and, for each repetition, asserts that the HI has switched to an expected program. |
| class [RepeatSideSpecificActionsWithIterationActions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).GenericActions/RepeatSideSpecificActionsWithIterationActionsType) | Repeats some action(s) a number of times and, at the end of each iteration, performs some other action(s). |
| class [SideSpecificActions](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).GenericActions/SideSpecificActionsType) | Represents an action that can combine side specific actions |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).HearingInstrumentActions namespace

| public type | description |
| --- | --- |
| class [ActivatePowerDownEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).HearingInstrumentActions/ActivatePowerDownEventType) | An action that simulates a power down event to the OS |
| class [AssociateHearingInstrument](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).HearingInstrumentActions/AssociateHearingInstrumentType) | An action that will associate the connected hearing instruments to the channel in use |
| class [ConnectAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).HearingInstrumentActions/ConnectActionType) | An action that connects the hearing instrument(s) to the current fitting session |
| class [CreateHi](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).HearingInstrumentActions/CreateHiType) | An action that creates a new instance of the hearing instrument and associates it with the [`HearingInstrumentContext`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).DeviceContexts/HearingInstrumentContextType) |
| class [FinalProgramming](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).HearingInstrumentActions/FinalProgrammingType) | An action that performs a final programming of the device(s) |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).MelodyPlayerActions namespace

| public type | description |
| --- | --- |
| class [AssertLastMelody](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).MelodyPlayerActions/AssertLastMelodyType) | Action that asserts that the last played melody was the expected |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).MirrorServiceActions namespace

| public type | description |
| --- | --- |
| class [AssertMirroredDataUnpacked](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).MirrorServiceActions/AssertMirroredDataUnpackedType) | Action that asserts that the Mirror Data Unpacked is synchronized between the devices. |
| class [AssertMirrorServiceOk](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).MirrorServiceActions/AssertMirrorServiceOkType) | An action that asserts that the mirror service is up and running. |
| class [EnablePresetMirrorService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).MirrorServiceActions/EnablePresetMirrorServiceType) | An action that enables/disables the preset mirror service (for the HI) |
| class [EnableVolumeMirrorService](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).MirrorServiceActions/EnableVolumeMirrorServiceType) | An action that enables/disables the volume mirror service for a single program |
| class [EnableVolumeMirrorServiceForAllPrograms](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).MirrorServiceActions/EnableVolumeMirrorServiceForAllProgramsType) | An action that enables/disables the volume mirror service for all programs |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions namespace

| public type | description |
| --- | --- |
| abstract class [AccessoryInitiatedPairingActionBase](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/AccessoryInitiatedPairingActionBaseType) | An action that triggers a 'start pairing' event at an accessory, and waits for the connection to stabilize. |
| class [AssertPairing](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/AssertPairingType) | Action that asserts that an accessory type is paired with the HI |
| class [AssertPairingTableCleared](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/AssertPairingTableClearedType) | Action that asserts that no accessories are paired with the HI |
| class [ClearPairingTable](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/ClearPairingTableType) | Action that clears the pairing table |
| class [PairHearingInstruments](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/PairHearingInstrumentsType) | An action that will pair the devices connected to the communication device associated with the HearingInstrumentContext |
| class [PairWithAccessory](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/PairWithAccessoryType) | Action that pairs the HI with the specified accessory (and via the specified channel, if applicable). |
| class [ResetPairingTable](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/ResetPairingTableType) | Action that Resets the whole pairing table to all zero addresses |
| class [SetupHearingInstrumentNetwork](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/SetupHearingInstrumentNetworkType) | An action that will setup a device to use specific network addresses |
| class [UnpairAccessory](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/UnpairAccessoryType) | Action that removes the pairings with a specific accessory type from the pairing table |
| class [UnpairAllStreamers](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/UnpairAllStreamersType) | Action that unpairs a HI from all streamers |
| class [UnpairHearingInstruments](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PairingActions/UnpairHearingInstrumentsType) | An action that will unpair the devices connected to the communication device associated with the HearingInstrumentContext |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions namespace

| public type | description |
| --- | --- |
| class [FittingBlockHandlerBleReadFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerBleReadFittingBlockType) | An action that reads fitting block over BLE. |
| class [FittingBlockHandlerBleWriteFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerBleWriteFittingBlockType) | An action that writes fitting block over BLE. |
| class [FittingBlockHandlerGetFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerGetFittingBlockType) | An action that gets fitting block and stores it in value context. |
| class [FittingBlockHandlerLegacyReadFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerLegacyReadFittingBlockType) | An action that reads fitting block (legacy). |
| class [FittingBlockHandlerLegacyWriteFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerLegacyWriteFittingBlockType) | An action that writes fitting block (legacy). |
| class [FittingBlockHandlerLoadFittingBlockFromData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerLoadFittingBlockFromDataType) | An action that loads fitting block from data. |
| class [FittingBlockHandlerReadFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerReadFittingBlockType) | An action that reads fitting block. |
| class [FittingBlockHandlerWriteFittingBlock](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerWriteFittingBlockType) | An action that writes fitting block. |
| class [FittingBlockHandlerWriteFittingBlockToBuffer](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/FittingBlockHandlerWriteFittingBlockToBufferType) | An action that writes fitting block to buffer. |
| class [PdsHandlingDoSave](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/PdsHandlingDoSaveType) | An action that saves PDS data. |
| class [PdsHandlingGetAddrRam](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/PdsHandlingGetAddrRamType) | An action that gets the address of PDS Ram and stores it in the test case context collection. |
| class [PdsHandlingGetSizeRam](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/PdsHandlingGetSizeRamType) | An action that gets the size of PDS Ram and stores it in the test case context collection. |
| class [PdsHandlingReadRamBuffer](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/PdsHandlingReadRamBufferType) | An action that reads Ram buffer of PDS and stores it in the test case context collection. |
| class [PdsHandlingWriteRamBuffer](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PdsCommandActions/PdsHandlingWriteRamBufferType) | An action that writes PDS Ram buffer. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions namespace

| public type | description |
| --- | --- |
| class [InitializeVectorProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/InitializeVectorProperty-1Type) | Action that sets the same value for all elements of a HI property of vector type. |
| class [ReadAllowedValues](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/ReadAllowedValuesType) | Action that reads the allowed values of a property and stores them within the test case context |
| class [ReadFilterCoefficients](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/ReadFilterCoefficientsType) | Action that reads the filter coefficients at the given property and converts them to a double[] using reflection. |
| class [ReadProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/ReadProperty-1Type) | Action that reads the value of a HI property. |
| class [ReadVariableAddress](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/ReadVariableAddressType) | Action that reads the address of a firmware variable |
| class [SetDatabasePropertyDefault&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/SetDatabasePropertyDefault-1Type) | An action that will reconfigure the default value for a specified property in the database |
| class [SetProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/SetProperty-1Type) | Action that sets the value of a HI property. |
| class [SetPropertyAndCheckResult&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/SetPropertyAndCheckResult-1Type) | Action the can set a property and then check if the result is as expected |
| class [SetPropertyFromContext&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/SetPropertyFromContext-1Type) | Action that sets the value of a HI property using a value stored in the test case context. |
| class [UpdateProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyAccessActions/UpdateProperty-1Type) | Action that updates the value of a HI property according to a provided onCallback function. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated namespace

| public type | description |
| --- | --- |
| class [BLEGNServicePropertyID](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/BLEGNServicePropertyIDType) | Identification of a single property or single vector element. |
| static class [OsBlackBoardFeatureProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/OsBlackBoardFeaturePropertyType) | Extension methods to add assert factories to the [`OsBlackBoardFeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/OsBlackBoardFeatureProperty-1Type) class |
| static class [OsFeatureProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/OsFeaturePropertyType) | Extension methods to add assert factories to the [`OsFeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/OsFeatureProperty-1Type) class |
| static class [PropertyFunctions&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/PropertyFunctions-1Type) | Collection of internal functions for reading/setting HI property values |
| static class [PropertyFunctionsBLEGNService&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/PropertyFunctionsBLEGNService-1Type) | Collection of internal functions for reading/setting BLE (REDACTED_COMPANY_ACRONYM) Service characteristic values |
| class [PropertyID](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/PropertyIDType) | Identification of a single property or single vector element. |
| abstract class [PropertyIDBase](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/PropertyIDBaseType) | Identification of a single property or single vector element. |
| static class [ReadFunction&lt;T,TPropertyId&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/ReadFunction-2Type) | Collection of functions for reading values from HI properties or from the user controlled test case context |
| static class [SoundProgramBlackBoardFeatureProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/SoundProgramBlackBoardFeaturePropertyType) | Extension methods to add assert factories to the [`SoundProgramBlackBoardFeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SoundProgramBlackBoardFeatureProperty-1Type) class |
| static class [SoundProgramCurveArrayProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/SoundProgramCurveArrayPropertyType) | Extension methods to add assert factories to the [`SoundProgramCurveArrayProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SoundProgramCurveArrayPropertyType) class |
| static class [SoundProgramFeatureProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/SoundProgramFeaturePropertyType) | Extension methods to add assert factories to the [`SoundProgramFeatureProperty`](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Features/SoundProgramFeatureProperty-1Type) class |
| class [StandardFeaturePropertiesCollection](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).PropertyRelated/StandardFeaturePropertiesCollectionType) | Collection of internal BLE-related helper functions |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).RecordingActions namespace

| public type | description |
| --- | --- |
| class [AssertAverageNoiseLevel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RecordingActions/AssertAverageNoiseLevelType) | Action that asserts the average noise level while executing other actions and saves it to the test case context |
| class [AssertDFSInitNoiseDuration](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RecordingActions/AssertDFSInitNoiseDurationType) | Action that performs a DFS initialisation with the noise duration set to the desired duration and asserts the actual duration matches it. |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions namespace

| public type | description |
| --- | --- |
| class [HomeEventFromRemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions/HomeEventFromRemoteControlType) | An action that triggers a 'home button pressed' event at a remote control |
| class [MuteEventFromRemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions/MuteEventFromRemoteControlType) | An action that triggers a 'mute button pressed' event at an RC |
| class [PairingEventFromRemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions/PairingEventFromRemoteControlType) | An action that triggers a 'start pairing' event at a remote control and waits for the pairing to succeed |
| class [ProgramChangeEventFromRemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions/ProgramChangeEventFromRemoteControlType) | An action that triggers a 'program switch' event at an RC |
| class [SasEventFromRemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions/SasEventFromRemoteControlType) | An action that triggers a 'SAS change' event at an RC |
| class [VolumeChangeEventFromRemoteControl](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).RemoteControlEventActions/VolumeChangeEventFromRemoteControlType) | An action that triggers a 'volume change' event from an RC |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).SatisfyActions namespace

| public type | description |
| --- | --- |
| class [CommitSatisfyProgress](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SatisfyActions/CommitSatisfyProgressType) | An Action that performs the CommitSatisfyProgress command and optionally persists the data |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions namespace

| public type | description |
| --- | --- |
| class [ActivateProgramShiftEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/ActivateProgramShiftEventType) | An action that triggers a program shift event to the OS |
| class [ActivateSasEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/ActivateSasEventType) | An action that simulates a change SAS event to the OS |
| class [AssertCurrentProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/AssertCurrentProgramType) | An action that asserts that the active program is the expected. |
| class [AssertCurrentProgramIsSAS](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/AssertCurrentProgramIsSASType) | An action that asserts that the active program is a SAS program. |
| class [AssertRcCausedResultingProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/AssertRcCausedResultingProgramType) | An action that asserts that the HI ends up in the expected resulting program, caused by an action, which is initiated by a Remote Control and when program mirror service is enabled. |
| class [AssertResultingProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/AssertResultingProgramType) | An action that asserts that the HI ends up in the expected resulting program, when program mirror service is enabled. |
| class [AssertWirelessStreamIsMixedIn](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/AssertWirelessStreamIsMixedInType) | An action that asserts whether a wireless stream is mixed-in or not |
| class [CreateSoundProgram](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/CreateSoundProgramType) | Action that creates a sound processing program (When the Hearing Instrument is connected to host, no presets exist) |
| class [EnterIPhoneProgramEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/EnterIPhoneProgramEventType) | An action that simulates an enter IPhone program event to the OS |
| class [SetInputMode](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/SetInputModeType) | An action that can set the input mode of a program. |
| class [SetNormalPresetCountAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/SetNormalPresetCountActionType) | Action that sets the number of normal presets on the hiContext hearing instrument |
| class [StartPresetWithAllBlackboardRecipies](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/StartPresetWithAllBlackboardRecipiesType) | Action that will inject all recipes onto the Blackboard and start the preset |
| class [StartProgramAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/StartProgramActionType) | An action that starts a sound processing program |
| class [SynchronizeProgramAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).SoundProgramActions/SynchronizeProgramActionType) | An action that synchronizes an online program |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).StationaryAudioStreamerEventActions namespace

| public type | description |
| --- | --- |
| class [PairingEventAtSas3](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StationaryAudioStreamerEventActions/PairingEventAtSas3Type) | An action that triggers a 'start pairing' event at a SAS and waits for the pairing to succeed |
| class [SelectStreamingModeEventAtSas3](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StationaryAudioStreamerEventActions/SelectStreamingModeEventAtSas3Type) | An action that triggers a 'select streaming mode' event at a SAS3 |
| class [StartSASStreaming](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StationaryAudioStreamerEventActions/StartSASStreamingType) | Action that starts SAS audio streaming |
| class [StopSASStreaming](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StationaryAudioStreamerEventActions/StopSASStreamingType) | Action that stops SAS audio streaming |
| class [VolumeChangeEventAtSas3](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StationaryAudioStreamerEventActions/VolumeChangeEventAtSas3Type) | An action that triggers a 'volume change' event at a SAS3 |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions namespace

| public type | description |
| --- | --- |
| class [AssertStandardFeatureProperty](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/AssertStandardFeaturePropertyType) | Action that asserts that a StandardFeature property of the GNAllStdFeatures/FirstFit has the expected value for the given program. |
| class [AssertStandardFeaturePropertyIsOK](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/AssertStandardFeaturePropertyIsOKType) | Action which asserts that a value of the specified Standard Feature within GNAllStdFeatures exists and has the expected valueID associated with the provided valueName in the dictionary. NOTE: Does not assert the selected value of the Standard Feature, asserts the integrity of the on-device property dictionary values. |
| class [ReadLayoutItemFromPersistentMemoryAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/ReadLayoutItemFromPersistentMemoryActionType) | An action that will read the layout item data from NVRAM to the PC model |
| class [ReadStorageLayoutProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/ReadStorageLayoutProperty-1Type) | Action that reads the value of a StorageLayout property. |
| class [SetDefaultFirstFitValuesForAllStandardFeaturesOfAllPrograms](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/SetDefaultFirstFitValuesForAllStandardFeaturesOfAllProgramsType) | Action that sets properties of all Standard Features of all programs to default FirstFit values. |
| class [SetStorageLayoutProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/SetStorageLayoutProperty-1Type) | Action that sets the value of a Storage Layout property and commits it to NVRAM. |
| class [UpdateLayoutProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/UpdateLayoutProperty-1Type) | Action that updates the value of a Storage Layout property according to a provided onCallback function to Storage Layout property and commits it to NVRAM. |
| class [WriteLayoutItemToPersistentMemoryAction](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayoutActions/WriteLayoutItemToPersistentMemoryActionType) | An action that will write the layout item data from the PC model to NVRAM |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayouts namespace

| public type | description |
| --- | --- |
| class [HardwareInitData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayouts/HardwareInitDataType) | Factory Class to access individual HardwareInitData properties |
| abstract class [StorageLayoutBase](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayouts/StorageLayoutBaseType) | Base class for Storage Layout factory classes to provide the generic read/write factories as well |
| class [StorageLayoutProperty&lt;T&gt;](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).StorageLayouts/StorageLayoutProperty-1Type) | Factory class to create read and set actions for specific StorageLayoutProperties |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).Types namespace

| public type | description |
| --- | --- |
| static class [CompressorGainCurves](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Types/CompressorGainCurvesType) | Static helper class for set/get linear CompressorGain curves on a hearing instrument |
| class [DFSData](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Types/DFSDataType) | DFS data |
| class [SecurityChallengeResultHelper](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Types/SecurityChallengeResultHelperType) | The SecurityChallenge result helper method |
| struct [ServiceCharacteristic](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Types/ServiceCharacteristicType) | A service characteristic |
| class [StandardFeatureProperties](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).Types/StandardFeaturePropertiesType) | Collection of Standard Feature properties |

## (REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions namespace

| public type | description |
| --- | --- |
| class [ActivateMicMinVolumeToggleEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/ActivateMicMinVolumeToggleEventType) | An action that simulates a toggle minimum Mic volume event to the OS Toggles between the minimum Mic volume and the previous volume (volume before toggle to minimum) |
| class [ActivateMuteEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/ActivateMuteEventType) | An action that simulates a mute event to the OS |
| class [ActivateVolumeDownEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/ActivateVolumeDownEventType) | An action that simulates a volume down event to the OS |
| class [ActivateVolumeUpEvent](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/ActivateVolumeUpEventType) | An action that simulates a volume up event to the OS |
| class [AdjustVolumeUsingSource](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AdjustVolumeUsingSourceType) | An action that will simulate a volume adjustment (or toggle mute state), initiated by either button/BLE/mirror/GATT. by manipulating the volume source symbol |
| class [AssertDefaultVolumeLevel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertDefaultVolumeLevelType) | An action that asserts that a volume level is at the default level. |
| class [AssertInitiatorMuteState](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertInitiatorMuteStateType) | An action that asserts that the mute state, initiated by either button/BLE/mirror/GATT for an audio source(s) of the active program is as expected. |
| class [AssertMaxVolumeLevel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertMaxVolumeLevelType) | An action that asserts that a volume level is as expected compared to maximum. |
| class [AssertMinVolumeLevel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertMinVolumeLevelType) | An action that asserts that a volume level is as expected compared to minimum. |
| class [AssertMuteState](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertMuteStateType) | An action that asserts that a mute state for the active program is as expected. |
| abstract class [AssertVolumeBase](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertVolumeBaseType) | An action that asserts that a volume level for the active program is as expected. |
| class [AssertVolumeLevel](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/AssertVolumeLevelType) | An action that asserts that a volume level for the active program is as expected. |
| class [EnsureMuteState](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/EnsureMuteStateType) | An action that ensures that the mute state, initiated by either button/BLE/mirror/GATT, of both mic and streamer of the currently active program become as desired. |
| class [ReadVolume](./(REDACTED).(REDACTED_OTHER_FRAMEWORK).VolumeControlActions/ReadVolumeType) | Reads a volume for the active program. |

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
