---
layout: default
title: BLE
grand_parent: (REDACTED_FRAMEWORK) API
parent: 0
has_children: True
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/BLEType
---
# BLE class

Factory for Bluetooth Low Energy (BLE)-related actions

```csharp
public static class BLE
```

## Public Members

| name | description |
| --- | --- |
| static [ConnectWithMangledAddress](BLE/ConnectWithMangledAddress) { get; } | Creates an action that tries to connect via BLE to a HI, using its mangled BLE address, which is constant and can always be used to connect to an HI in either DFU or Service mode, but not in normal mode |
| static [Disconnect](BLE/Disconnect) { get; } | Creates an action that disconnects a BLE connection against an HI. |
| static [DiscoverServices](BLE/DiscoverServices) { get; } | Creates an action that discovers BLE services, other than the (REDACTED_COMPANY_ACRONYM) service |
| static [IsNotConnected](BLE/IsNotConnected) { get; } | Creates an action that asserts that the HI is not connected via BLE. |
| static [PerformBonding](BLE/PerformBonding) { get; } | Creates an action that performs bonding with the connected device |
| static [Scan](BLE/Scan) { get; } | Creates an action that performs a wireless scan (via BLE) for all HIs. |
| static [SetAndCheckGNCharacteristicsWithAuthentication](BLE/SetAndCheckGNCharacteristicsWithAuthentication) { get; } | Creates an action that discovers all BLE (REDACTED_COMPANY_ACRONYM) service characteristics, which require authentication, and verifies that they can be read and set (whatever is enabled). |
| static [SetAndCheckGNCharacteristicsWithoutAuthentication](BLE/SetAndCheckGNCharacteristicsWithoutAuthentication) { get; } | Creates an action that discovers all BLE (REDACTED_COMPANY_ACRONYM) service characteristics, which do not require authentication, and verifies that they can be read and set (whatever is enabled). |
| const [NoLimitVectorIndex](BLE/NoLimitVectorIndex) | Index of the value to compare with has no meaning, since it is not a vector. |
| const [SameAsActualVectorIndex](BLE/SameAsActualVectorIndex) | Index of the value to compare with must be the same as the index of the actual value, which also works if they both are NOT vectors. |
| static [AssertCharacteristic&lt;T&gt;](BLE/AssertCharacteristic)(…) | Creates an action that asserts that the value of a BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected. |
| static [AssertCharacteristicConfiguration](BLE/AssertCharacteristicConfiguration)(…) | Creates an action that asserts that a (REDACTED_COMPANY_ACRONYM) service characteristic is readable/writable and can be notified or not. (2 methods) |
| static [AssertCharacteristicNotified](BLE/AssertCharacteristicNotified)(…) | Creates an action that asserts that a BLE (REDACTED_COMPANY_ACRONYM) service characteristic received a notification. (2 methods) |
| static [AssertCharacteristicWithNamedValue&lt;T,T1&gt;](BLE/AssertCharacteristicWithNamedValue)(…) | Creates an action that asserts that the value of a BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected. |
| static [AssertCorrespondingCharacteristicsConfiguration](BLE/AssertCorrespondingCharacteristicsConfiguration)(…) | Creates an action that asserts that the corresponding BLE Audio (LEA) and (REDACTED_COMPANY_ACRONYM) service characteristics have the correct Read/Write/Notify properties. |
| static [AssertGNSetNotifiesLEA](BLE/AssertGNSetNotifiesLEA)(…) | Creates an action that asserts that setting a BLE (REDACTED_COMPANY_ACRONYM) service characteristic notifies a BLE Audio (LEA) service characteristic. |
| static [AssertHISecurityCapabilities](BLE/AssertHISecurityCapabilities)() | Creates an action that verifies the accessibility and state of the security capabilities of the HI |
| static [AssertLEASetNotifiesGN](BLE/AssertLEASetNotifiesGN)(…) | Creates an action that asserts that setting a BLE Audio (LEA) service characteristic notifies a (REDACTED_COMPANY_ACRONYM) service characteristic. |
| static [AssertNotPairedCharacteristicsLength](BLE/AssertNotPairedCharacteristicsLength)(…) | Creates an action that asserts not paired BLE service characteristics have the expected length. (2 methods) |
| static [AssertPairedCharacteristicsLength](BLE/AssertPairedCharacteristicsLength)(…) | Creates an action that asserts paired BLE service characteristics have the expected length. (2 methods) |
| static [AssertVector&lt;T&gt;](BLE/AssertVector)(…) | Creates an action that asserts that the value of a vector type BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected. |
| static [AssertVectorElement&lt;T&gt;](BLE/AssertVectorElement)(…) | Creates an action that asserts that the value of an individual element of a vector type BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected. |
| static [AssertVectorElementWithNamedValue&lt;T,T1&gt;](BLE/AssertVectorElementWithNamedValue)(…) | Creates an action that asserts that the value of an individual element of a vector type BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected. |
| static [AssertVectorWithNamedValue&lt;T,T1&gt;](BLE/AssertVectorWithNamedValue)(…) | Creates an action that asserts that the value of a vector type BLE (REDACTED_COMPANY_ACRONYM) service characteristic is as expected. |
| static [BootAndScan](BLE/BootAndScan)(…) | Creates an action that performs a boot of the HI into offline (not in host) mode, then a wireless scan via BLE for HIs. |
| static [BootScanAndBond](BLE/BootScanAndBond)(…) | Creates an action that performs: boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers services performs bonding |
| static [BootScanAndConnect](BLE/BootScanAndConnect)(…) | Creates an action that performs a boot of the HI into offline (not in host) mode, then a wireless scan via BLE for HIs and connects (via BLE) to the HI. |
| static [BootScanAndConnectGN](BLE/BootScanAndConnectGN)(…) | Creates an action that performs: boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers (REDACTED_COMPANY_ACRONYM) service characteristics (MIC enabled) |
| static [BootScanAndConnectGNMICDisabled](BLE/BootScanAndConnectGNMICDisabled)(…) | Creates an action that performs: boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers (REDACTED_COMPANY_ACRONYM) service characteristics (MIC disabled) |
| static [BootScanConnectGNAndBond](BLE/BootScanConnectGNAndBond)(…) | Creates an action that performs: boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers services discovers (REDACTED_COMPANY_ACRONYM) service characteristics (MIC enabled) performs bonding |
| static [BootScanConnectGNWithMICDisabledAndBond](BLE/BootScanConnectGNWithMICDisabledAndBond)(…) | Creates an action that performs: boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers services discovers (REDACTED_COMPANY_ACRONYM) service characteristics (MIC disabled) performs bonding |
| static [Connect](BLE/Connect)(…) | Creates an action that tries to connect via BLE to a HI, using its device name. |
| static [ConnectWithAddress](BLE/ConnectWithAddress)(…) | Creates an action that tries to connect via BLE to a HI, using its Bluetooth address. |
| static [ConnectWithName](BLE/ConnectWithName)(…) | Creates an action that tries to connect via BLE to a HI, using its device name. |
| static [DiscoverGNCharacteristics](BLE/DiscoverGNCharacteristics)(…) | Creates an action that authenticates via BLE (REDACTED_COMPANY_ACRONYM) service and discovers BLE (REDACTED_COMPANY_ACRONYM) service characteristics |
| static [FinalProgrammingBootScanAndBond](BLE/FinalProgrammingBootScanAndBond)(…) | Creates an action that performs: final program the HI boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers services performs bonding |
| static [FinalProgrammingBootScanAndConnect](BLE/FinalProgrammingBootScanAndConnect)(…) | Creates an action that performs: final program the HI boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI |
| static [FinalProgrammingBootScanAndConnectGN](BLE/FinalProgrammingBootScanAndConnectGN)(…) | Creates an action that performs: final program the HI boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers (REDACTED_COMPANY_ACRONYM) service characteristics |
| static [FinalProgrammingBootScanConnectGNAndBond](BLE/FinalProgrammingBootScanConnectGNAndBond)(…) | Creates an action that performs: final program the HI boot the HI into offline (not in host) mode wireless scan via BLE for HIs connects to the HI discovers services discovers (REDACTED_COMPANY_ACRONYM) service characteristics performs bonding |
| static [FittingServiceEvent](BLE/FittingServiceEvent)(…) | Creates an action that sets the value of a BLE fitting service event, hence executing it Go to SAS preset (online) to demo SAS: Demo start/stop is triggered by button in the FSW. FSW will make sure it is paired. FSW will stop demo properly for example before changing preset, before final programming |
| static [FittingServiceShiftProgram](BLE/FittingServiceShiftProgram)(…) | Creates an action that shifts the program (preset) via BLE fitting service |
| static [GetAdvertisedData](BLE/GetAdvertisedData)(…) | Creates an action that collects advertised ADV_IND and SCN_RSP data from the currently connected HI and stores the value in the test case context under the specified name (default: "AdvertisedData") |
| static [GNAuthenticate](BLE/GNAuthenticate)(…) | BLE (REDACTED_COMPANY_ACRONYM) service authentication |
| static [IsDiscoverableDevice](BLE/IsDiscoverableDevice)(…) | Creates an action that asserts that the specified device is discoverable via BLE. |
| static [IsDiscoverableService](BLE/IsDiscoverableService)(…) | Creates an action that asserts that the specified BLE service is discoverable. |
| static [IsServiceAdvertised](BLE/IsServiceAdvertised)(…) | Creates an action that asserts that the specified BLE service is advertised. |
| static [NegotiateMaxMTU](BLE/NegotiateMaxMTU)(…) | Creates an action that negotiates the Maximum MTU size via BLE |
| static [Read](BLE/Read)(…) | Creates an action that reads a BLE service characteristic (2 methods) |
| static [ReadNotification](BLE/ReadNotification)(…) | Reads the last received characteristic notification for the specified service. |
| static [ScanAndConnect](BLE/ScanAndConnect)(…) | Creates an action that performs a wireless scan (via BLE) for all HIs and then tries to connect via BLE to this HI, using its device name. |
| static [ScanSetDeviceName](BLE/ScanSetDeviceName)(…) | Creates an action that sets the GAP device name and performs a wireless scan (via BLE) for all HIs. |
| static [Set](BLE/Set)(…) | Creates an action that sets the value of a BLE service characteristic (2 methods) |
| static [SubscribeForNotification](BLE/SubscribeForNotification)(…) | Creates an action that subscribes for a BLE (REDACTED_COMPANY_ACRONYM) service characteristic notification. (2 methods) |
| static [Update](BLE/Update)(…) | Creates an action that updates the value of a BLE characteristic (2 methods) |

## See Also

* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskNamespace)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
