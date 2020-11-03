---
title: "Update windows10EndpointProtectionConfiguration"
description: "Update the properties of a windows10EndpointProtectionConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update windows10EndpointProtectionConfiguration
Namespace: microsoft.graph

Update the properties of a [windows10EndpointProtectionConfiguration](../resources/windows10endpointprotectionconfiguration.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH ** Entity URI for microsoft.graph.windows10EndpointProtectionConfiguration not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [windows10EndpointProtectionConfiguration](../resources/windows10endpointprotectionconfiguration.md) object.

The following table shows the properties that are required when you create the [windows10EndpointProtectionConfiguration](../resources/windows10endpointprotectionconfiguration.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|roleScopeTagIds|String collection|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|supportsScopeTags|Boolean|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsEdition|[deviceManagementApplicabilityRuleOsEdition](../resources/intune-devicemanagementapplicabilityruleosedition.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsVersion|[deviceManagementApplicabilityRuleOsVersion](../resources/intune-devicemanagementapplicabilityruleosversion.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleDeviceMode|[deviceManagementApplicabilityRuleDeviceMode](../resources/intune-devicemanagementapplicabilityruledevicemode.md)|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|description|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|displayName|String|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|version|Int32|**TODO: Add Description** Inherited from [deviceConfiguration](../resources/intune-deviceconfiguration.md)|
|dmaGuardDeviceEnumerationPolicy|dmaGuardDeviceEnumerationPolicyType|**TODO: Add Description**. Possible values are: `deviceDefault`, `blockAll`, `allowAll`.|
|firewallRules|[windowsFirewallRule](../resources/intune-windowsfirewallrule.md) collection|**TODO: Add Description**|
|userRightsAccessCredentialManagerAsTrustedCaller|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsAllowAccessFromNetwork|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsBlockAccessFromNetwork|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsActAsPartOfTheOperatingSystem|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsLocalLogOn|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsDenyLocalLogOn|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsBackupData|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsChangeSystemTime|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsCreateGlobalObjects|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsCreatePageFile|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsCreatePermanentSharedObjects|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsCreateSymbolicLinks|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsCreateToken|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsDebugPrograms|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsRemoteDesktopServicesLogOn|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsDelegation|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsGenerateSecurityAudits|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsImpersonateClient|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsIncreaseSchedulingPriority|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsLoadUnloadDrivers|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsLockMemory|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsManageAuditingAndSecurityLogs|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsManageVolumes|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsModifyFirmwareEnvironment|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsModifyObjectLabels|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsProfileSingleProcess|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsRemoteShutdown|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsRestoreData|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|userRightsTakeOwnership|[deviceManagementUserRightsSetting](../resources/intune-devicemanagementuserrightssetting.md)|**TODO: Add Description**|
|xboxServicesEnableXboxGameSaveTask|Boolean|**TODO: Add Description**|
|xboxServicesAccessoryManagementServiceStartupMode|serviceStartType|**TODO: Add Description**. Possible values are: `manual`, `automatic`, `disabled`.|
|xboxServicesLiveAuthManagerServiceStartupMode|serviceStartType|**TODO: Add Description**. Possible values are: `manual`, `automatic`, `disabled`.|
|xboxServicesLiveGameSaveServiceStartupMode|serviceStartType|**TODO: Add Description**. Possible values are: `manual`, `automatic`, `disabled`.|
|xboxServicesLiveNetworkingServiceStartupMode|serviceStartType|**TODO: Add Description**. Possible values are: `manual`, `automatic`, `disabled`.|
|localSecurityOptionsBlockMicrosoftAccounts|Boolean|**TODO: Add Description**|
|localSecurityOptionsBlockRemoteLogonWithBlankPassword|Boolean|**TODO: Add Description**|
|localSecurityOptionsDisableAdministratorAccount|Boolean|**TODO: Add Description**|
|localSecurityOptionsAdministratorAccountName|String|**TODO: Add Description**|
|localSecurityOptionsDisableGuestAccount|Boolean|**TODO: Add Description**|
|localSecurityOptionsGuestAccountName|String|**TODO: Add Description**|
|localSecurityOptionsAllowUndockWithoutHavingToLogon|Boolean|**TODO: Add Description**|
|localSecurityOptionsBlockUsersInstallingPrinterDrivers|Boolean|**TODO: Add Description**|
|localSecurityOptionsBlockRemoteOpticalDriveAccess|Boolean|**TODO: Add Description**|
|localSecurityOptionsFormatAndEjectOfRemovableMediaAllowedUser|localSecurityOptionsFormatAndEjectOfRemovableMediaAllowedUserType|**TODO: Add Description**. Possible values are: `notConfigured`, `administrators`, `administratorsAndPowerUsers`, `administratorsAndInteractiveUsers`.|
|localSecurityOptionsMachineInactivityLimit|Int32|**TODO: Add Description**|
|localSecurityOptionsMachineInactivityLimitInMinutes|Int32|**TODO: Add Description**|
|localSecurityOptionsDoNotRequireCtrlAltDel|Boolean|**TODO: Add Description**|
|localSecurityOptionsHideLastSignedInUser|Boolean|**TODO: Add Description**|
|localSecurityOptionsHideUsernameAtSignIn|Boolean|**TODO: Add Description**|
|localSecurityOptionsLogOnMessageTitle|String|**TODO: Add Description**|
|localSecurityOptionsLogOnMessageText|String|**TODO: Add Description**|
|localSecurityOptionsAllowPKU2UAuthenticationRequests|Boolean|**TODO: Add Description**|
|localSecurityOptionsAllowRemoteCallsToSecurityAccountsManagerHelperBool|Boolean|**TODO: Add Description**|
|localSecurityOptionsAllowRemoteCallsToSecurityAccountsManager|String|**TODO: Add Description**|
|localSecurityOptionsMinimumSessionSecurityForNtlmSspBasedClients|localSecurityOptionsMinimumSessionSecurity|**TODO: Add Description**. Possible values are: `none`, `requireNtmlV2SessionSecurity`, `require128BitEncryption`, `ntlmV2And128BitEncryption`.|
|localSecurityOptionsMinimumSessionSecurityForNtlmSspBasedServers|localSecurityOptionsMinimumSessionSecurity|**TODO: Add Description**. Possible values are: `none`, `requireNtmlV2SessionSecurity`, `require128BitEncryption`, `ntlmV2And128BitEncryption`.|
|lanManagerAuthenticationLevel|lanManagerAuthenticationLevel|**TODO: Add Description**. Possible values are: `lmAndNltm`, `lmNtlmAndNtlmV2`, `lmAndNtlmOnly`, `lmAndNtlmV2`, `lmNtlmV2AndNotLm`, `lmNtlmV2AndNotLmOrNtm`.|
|lanManagerWorkstationDisableInsecureGuestLogons|Boolean|**TODO: Add Description**|
|localSecurityOptionsClearVirtualMemoryPageFile|Boolean|**TODO: Add Description**|
|localSecurityOptionsAllowSystemToBeShutDownWithoutHavingToLogOn|Boolean|**TODO: Add Description**|
|localSecurityOptionsAllowUIAccessApplicationElevation|Boolean|**TODO: Add Description**|
|localSecurityOptionsVirtualizeFileAndRegistryWriteFailuresToPerUserLocations|Boolean|**TODO: Add Description**|
|localSecurityOptionsOnlyElevateSignedExecutables|Boolean|**TODO: Add Description**|
|localSecurityOptionsAdministratorElevationPromptBehavior|localSecurityOptionsAdministratorElevationPromptBehaviorType|**TODO: Add Description**. Possible values are: `notConfigured`, `elevateWithoutPrompting`, `promptForCredentialsOnTheSecureDesktop`, `promptForConsentOnTheSecureDesktop`, `promptForCredentials`, `promptForConsent`, `promptForConsentForNonWindowsBinaries`.|
|localSecurityOptionsStandardUserElevationPromptBehavior|localSecurityOptionsStandardUserElevationPromptBehaviorType|**TODO: Add Description**. Possible values are: `notConfigured`, `automaticallyDenyElevationRequests`, `promptForCredentialsOnTheSecureDesktop`, `promptForCredentials`.|
|localSecurityOptionsSwitchToSecureDesktopWhenPromptingForElevation|Boolean|**TODO: Add Description**|
|localSecurityOptionsDetectApplicationInstallationsAndPromptForElevation|Boolean|**TODO: Add Description**|
|localSecurityOptionsAllowUIAccessApplicationsForSecureLocations|Boolean|**TODO: Add Description**|
|localSecurityOptionsUseAdminApprovalMode|Boolean|**TODO: Add Description**|
|localSecurityOptionsUseAdminApprovalModeForAdministrators|Boolean|**TODO: Add Description**|
|localSecurityOptionsInformationShownOnLockScreen|localSecurityOptionsInformationShownOnLockScreenType|**TODO: Add Description**. Possible values are: `notConfigured`, `userDisplayNameDomainUser`, `userDisplayNameOnly`, `doNotDisplayUser`.|
|localSecurityOptionsInformationDisplayedOnLockScreen|localSecurityOptionsInformationDisplayedOnLockScreenType|**TODO: Add Description**. Possible values are: `notConfigured`, `administrators`, `administratorsAndPowerUsers`, `administratorsAndInteractiveUsers`.|
|localSecurityOptionsDisableClientDigitallySignCommunicationsIfServerAgrees|Boolean|**TODO: Add Description**|
|localSecurityOptionsClientDigitallySignCommunicationsAlways|Boolean|**TODO: Add Description**|
|localSecurityOptionsClientSendUnencryptedPasswordToThirdPartySMBServers|Boolean|**TODO: Add Description**|
|localSecurityOptionsDisableServerDigitallySignCommunicationsAlways|Boolean|**TODO: Add Description**|
|localSecurityOptionsDisableServerDigitallySignCommunicationsIfClientAgrees|Boolean|**TODO: Add Description**|
|localSecurityOptionsRestrictAnonymousAccessToNamedPipesAndShares|Boolean|**TODO: Add Description**|
|localSecurityOptionsDoNotAllowAnonymousEnumerationOfSAMAccounts|Boolean|**TODO: Add Description**|
|localSecurityOptionsAllowAnonymousEnumerationOfSAMAccountsAndShares|Boolean|**TODO: Add Description**|
|localSecurityOptionsDoNotStoreLANManagerHashValueOnNextPasswordChange|Boolean|**TODO: Add Description**|
|localSecurityOptionsSmartCardRemovalBehavior|localSecurityOptionsSmartCardRemovalBehaviorType|**TODO: Add Description**. Possible values are: `lockWorkstation`, `noAction`, `forceLogoff`, `disconnectRemoteDesktopSession`.|
|defenderSecurityCenterDisableAppBrowserUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableFamilyUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableHealthUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableNetworkUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableVirusUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableAccountUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableClearTpmUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableHardwareUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableNotificationAreaUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableRansomwareUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableSecureBootUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableTroubleshootingUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterDisableVulnerableTpmFirmwareUpdateUI|Boolean|**TODO: Add Description**|
|defenderSecurityCenterOrganizationDisplayName|String|**TODO: Add Description**|
|defenderSecurityCenterHelpEmail|String|**TODO: Add Description**|
|defenderSecurityCenterHelpPhone|String|**TODO: Add Description**|
|defenderSecurityCenterHelpURL|String|**TODO: Add Description**|
|defenderSecurityCenterNotificationsFromApp|defenderSecurityCenterNotificationsFromAppType|**TODO: Add Description**. Possible values are: `notConfigured`, `blockNoncriticalNotifications`, `blockAllNotifications`.|
|defenderSecurityCenterITContactDisplay|defenderSecurityCenterITContactDisplayType|**TODO: Add Description**. Possible values are: `notConfigured`, `displayInAppAndInNotifications`, `displayOnlyInApp`, `displayOnlyInNotifications`.|
|windowsDefenderTamperProtection|windowsDefenderTamperProtectionOptions|**TODO: Add Description**. Possible values are: `notConfigured`, `enable`, `disable`.|
|firewallBlockStatefulFTP|Boolean|**TODO: Add Description**|
|firewallIdleTimeoutForSecurityAssociationInSeconds|Int32|**TODO: Add Description**|
|firewallPreSharedKeyEncodingMethod|firewallPreSharedKeyEncodingMethodType|**TODO: Add Description**. Possible values are: `deviceDefault`, `none`, `utF8`.|
|firewallIPSecExemptionsNone|Boolean|**TODO: Add Description**|
|firewallIPSecExemptionsAllowNeighborDiscovery|Boolean|**TODO: Add Description**|
|firewallIPSecExemptionsAllowICMP|Boolean|**TODO: Add Description**|
|firewallIPSecExemptionsAllowRouterDiscovery|Boolean|**TODO: Add Description**|
|firewallIPSecExemptionsAllowDHCP|Boolean|**TODO: Add Description**|
|firewallCertificateRevocationListCheckMethod|firewallCertificateRevocationListCheckMethodType|**TODO: Add Description**. Possible values are: `deviceDefault`, `none`, `attempt`, `require`.|
|firewallMergeKeyingModuleSettings|Boolean|**TODO: Add Description**|
|firewallPacketQueueingMethod|firewallPacketQueueingMethodType|**TODO: Add Description**. Possible values are: `deviceDefault`, `disabled`, `queueInbound`, `queueOutbound`, `queueBoth`.|
|firewallProfileDomain|[windowsFirewallNetworkProfile](../resources/intune-windowsfirewallnetworkprofile.md)|**TODO: Add Description**|
|firewallProfilePublic|[windowsFirewallNetworkProfile](../resources/intune-windowsfirewallnetworkprofile.md)|**TODO: Add Description**|
|firewallProfilePrivate|[windowsFirewallNetworkProfile](../resources/intune-windowsfirewallnetworkprofile.md)|**TODO: Add Description**|
|defenderAdobeReaderLaunchChildProcess|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderAttackSurfaceReductionExcludedPaths|String collection|**TODO: Add Description**|
|defenderOfficeAppsOtherProcessInjectionType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderOfficeAppsOtherProcessInjection|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderOfficeCommunicationAppsLaunchChildProcess|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderOfficeAppsExecutableContentCreationOrLaunchType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderOfficeAppsExecutableContentCreationOrLaunch|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderOfficeAppsLaunchChildProcessType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderOfficeAppsLaunchChildProcess|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderOfficeMacroCodeAllowWin32ImportsType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderOfficeMacroCodeAllowWin32Imports|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderScriptObfuscatedMacroCodeType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderScriptObfuscatedMacroCode|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderScriptDownloadedPayloadExecutionType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderScriptDownloadedPayloadExecution|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderPreventCredentialStealingType|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderProcessCreationType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderProcessCreation|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderUntrustedUSBProcessType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderUntrustedUSBProcess|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderUntrustedExecutableType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderUntrustedExecutable|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderEmailContentExecutionType|defenderAttackSurfaceType|**TODO: Add Description**. Possible values are: `userDefined`, `block`, `auditMode`.|
|defenderEmailContentExecution|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderAdvancedRansomewareProtectionType|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderGuardMyFoldersType|folderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`, `blockDiskModification`, `auditDiskModification`.|
|defenderGuardedFoldersAllowedAppPaths|String collection|**TODO: Add Description**|
|defenderAdditionalGuardedFolders|String collection|**TODO: Add Description**|
|defenderNetworkProtectionType|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderExploitProtectionXml|Binary|**TODO: Add Description**|
|defenderExploitProtectionXmlFileName|String|**TODO: Add Description**|
|defenderSecurityCenterBlockExploitProtectionOverride|Boolean|**TODO: Add Description**|
|appLockerApplicationControl|appLockerApplicationControlType|**TODO: Add Description**. Possible values are: `notConfigured`, `enforceComponentsAndStoreApps`, `auditComponentsAndStoreApps`, `enforceComponentsStoreAppsAndSmartlocker`, `auditComponentsStoreAppsAndSmartlocker`.|
|deviceGuardLocalSystemAuthorityCredentialGuardSettings|deviceGuardLocalSystemAuthorityCredentialGuardType|**TODO: Add Description**. Possible values are: `notConfigured`, `enableWithUEFILock`, `enableWithoutUEFILock`, `disable`.|
|deviceGuardEnableVirtualizationBasedSecurity|Boolean|**TODO: Add Description**|
|deviceGuardEnableSecureBootWithDMA|Boolean|**TODO: Add Description**|
|deviceGuardSecureBootWithDMA|secureBootWithDMAType|**TODO: Add Description**. Possible values are: `notConfigured`, `withoutDMA`, `withDMA`.|
|deviceGuardLaunchSystemGuard|enablement|**TODO: Add Description**. Possible values are: `notConfigured`, `enabled`, `disabled`.|
|smartScreenEnableInShell|Boolean|**TODO: Add Description**|
|smartScreenBlockOverrideForFiles|Boolean|**TODO: Add Description**|
|applicationGuardEnabled|Boolean|**TODO: Add Description**|
|applicationGuardEnabledOptions|applicationGuardEnabledOptions|**TODO: Add Description**. Possible values are: `notConfigured`, `enabledForEdge`, `enabledForOffice`, `enabledForEdgeAndOffice`.|
|applicationGuardBlockFileTransfer|applicationGuardBlockFileTransferType|**TODO: Add Description**. Possible values are: `notConfigured`, `blockImageAndTextFile`, `blockImageFile`, `blockNone`, `blockTextFile`.|
|applicationGuardBlockNonEnterpriseContent|Boolean|**TODO: Add Description**|
|applicationGuardAllowPersistence|Boolean|**TODO: Add Description**|
|applicationGuardForceAuditing|Boolean|**TODO: Add Description**|
|applicationGuardBlockClipboardSharing|applicationGuardBlockClipboardSharingType|**TODO: Add Description**. Possible values are: `notConfigured`, `blockBoth`, `blockHostToContainer`, `blockContainerToHost`, `blockNone`.|
|applicationGuardAllowPrintToPDF|Boolean|**TODO: Add Description**|
|applicationGuardAllowPrintToXPS|Boolean|**TODO: Add Description**|
|applicationGuardAllowPrintToLocalPrinters|Boolean|**TODO: Add Description**|
|applicationGuardAllowPrintToNetworkPrinters|Boolean|**TODO: Add Description**|
|applicationGuardAllowVirtualGPU|Boolean|**TODO: Add Description**|
|applicationGuardAllowFileSaveOnHost|Boolean|**TODO: Add Description**|
|bitLockerAllowStandardUserEncryption|Boolean|**TODO: Add Description**|
|bitLockerDisableWarningForOtherDiskEncryption|Boolean|**TODO: Add Description**|
|bitLockerEnableStorageCardEncryptionOnMobile|Boolean|**TODO: Add Description**|
|bitLockerEncryptDevice|Boolean|**TODO: Add Description**|
|bitLockerSystemDrivePolicy|[bitLockerSystemDrivePolicy](../resources/intune-bitlockersystemdrivepolicy.md)|**TODO: Add Description**|
|bitLockerFixedDrivePolicy|[bitLockerFixedDrivePolicy](../resources/intune-bitlockerfixeddrivepolicy.md)|**TODO: Add Description**|
|bitLockerRemovableDrivePolicy|[bitLockerRemovableDrivePolicy](../resources/intune-bitlockerremovabledrivepolicy.md)|**TODO: Add Description**|
|bitLockerRecoveryPasswordRotation|bitLockerRecoveryPasswordRotationType|**TODO: Add Description**. Possible values are: `notConfigured`, `disabled`, `enabledForAzureAd`, `enabledForAzureAdAndHybrid`.|
|defenderDisableScanArchiveFiles|Boolean|**TODO: Add Description**|
|defenderAllowScanArchiveFiles|Boolean|**TODO: Add Description**|
|defenderDisableBehaviorMonitoring|Boolean|**TODO: Add Description**|
|defenderAllowBehaviorMonitoring|Boolean|**TODO: Add Description**|
|defenderDisableCloudProtection|Boolean|**TODO: Add Description**|
|defenderAllowCloudProtection|Boolean|**TODO: Add Description**|
|defenderEnableScanIncomingMail|Boolean|**TODO: Add Description**|
|defenderEnableScanMappedNetworkDrivesDuringFullScan|Boolean|**TODO: Add Description**|
|defenderDisableScanRemovableDrivesDuringFullScan|Boolean|**TODO: Add Description**|
|defenderAllowScanRemovableDrivesDuringFullScan|Boolean|**TODO: Add Description**|
|defenderDisableScanDownloads|Boolean|**TODO: Add Description**|
|defenderAllowScanDownloads|Boolean|**TODO: Add Description**|
|defenderDisableIntrusionPreventionSystem|Boolean|**TODO: Add Description**|
|defenderAllowIntrusionPreventionSystem|Boolean|**TODO: Add Description**|
|defenderDisableOnAccessProtection|Boolean|**TODO: Add Description**|
|defenderAllowOnAccessProtection|Boolean|**TODO: Add Description**|
|defenderDisableRealTimeMonitoring|Boolean|**TODO: Add Description**|
|defenderAllowRealTimeMonitoring|Boolean|**TODO: Add Description**|
|defenderDisableScanNetworkFiles|Boolean|**TODO: Add Description**|
|defenderAllowScanNetworkFiles|Boolean|**TODO: Add Description**|
|defenderDisableScanScriptsLoadedInInternetExplorer|Boolean|**TODO: Add Description**|
|defenderAllowScanScriptsLoadedInInternetExplorer|Boolean|**TODO: Add Description**|
|defenderBlockEndUserAccess|Boolean|**TODO: Add Description**|
|defenderAllowEndUserAccess|Boolean|**TODO: Add Description**|
|defenderScanMaxCpuPercentage|Int32|**TODO: Add Description**|
|defenderCheckForSignaturesBeforeRunningScan|Boolean|**TODO: Add Description**|
|defenderCloudBlockLevel|defenderCloudBlockLevelType|**TODO: Add Description**. Possible values are: `notConfigured`, `high`, `highPlus`, `zeroTolerance`.|
|defenderCloudExtendedTimeoutInSeconds|Int32|**TODO: Add Description**|
|defenderDaysBeforeDeletingQuarantinedMalware|Int32|**TODO: Add Description**|
|defenderDisableCatchupFullScan|Boolean|**TODO: Add Description**|
|defenderDisableCatchupQuickScan|Boolean|**TODO: Add Description**|
|defenderEnableLowCpuPriority|Boolean|**TODO: Add Description**|
|defenderFileExtensionsToExclude|String collection|**TODO: Add Description**|
|defenderFilesAndFoldersToExclude|String collection|**TODO: Add Description**|
|defenderProcessesToExclude|String collection|**TODO: Add Description**|
|defenderPotentiallyUnwantedAppAction|defenderProtectionType|**TODO: Add Description**. Possible values are: `userDefined`, `enable`, `auditMode`.|
|defenderScanDirection|defenderRealtimeScanDirection|**TODO: Add Description**. Possible values are: `monitorAllFiles`, `monitorIncomingFilesOnly`, `monitorOutgoingFilesOnly`.|
|defenderScanType|defenderScanType|**TODO: Add Description**. Possible values are: `userDefined`, `disabled`, `quick`, `full`.|
|defenderScheduledQuickScanTime|TimeOfDay|**TODO: Add Description**|
|defenderScheduledScanDay|weeklySchedule|**TODO: Add Description**. Possible values are: `userDefined`, `everyday`, `sunday`, `monday`, `tuesday`, `wednesday`, `thursday`, `friday`, `saturday`, `noScheduledScan`.|
|defenderScheduledScanTime|TimeOfDay|**TODO: Add Description**|
|defenderSignatureUpdateIntervalInHours|Int32|**TODO: Add Description**|
|defenderSubmitSamplesConsentType|defenderSubmitSamplesConsentType|**TODO: Add Description**. Possible values are: `sendSafeSamplesAutomatically`, `alwaysPrompt`, `neverSend`, `sendAllSamplesAutomatically`.|
|defenderDetectedMalwareActions|[defenderDetectedMalwareActions](../resources/intune-defenderdetectedmalwareactions.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [windows10EndpointProtectionConfiguration](../resources/windows10endpointprotectionconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_windows10endpointprotectionconfiguration"
}
-->
``` http
PATCH https://graph.microsoft.com/beta** Entity URI for microsoft.graph.windows10EndpointProtectionConfiguration not found
Content-Type: application/json
Content-length: 15713

{
  "@odata.type": "#microsoft.graph.windows10EndpointProtectionConfiguration",
  "roleScopeTagIds": [
    "String"
  ],
  "supportsScopeTags": "Boolean",
  "deviceManagementApplicabilityRuleOsEdition": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition"
  },
  "deviceManagementApplicabilityRuleOsVersion": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion"
  },
  "deviceManagementApplicabilityRuleDeviceMode": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode"
  },
  "description": "String",
  "displayName": "String",
  "version": "Integer",
  "dmaGuardDeviceEnumerationPolicy": "String",
  "firewallRules": [
    {
      "@odata.type": "microsoft.graph.windowsFirewallRule"
    }
  ],
  "userRightsAccessCredentialManagerAsTrustedCaller": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsAllowAccessFromNetwork": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsBlockAccessFromNetwork": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsActAsPartOfTheOperatingSystem": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsLocalLogOn": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsDenyLocalLogOn": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsBackupData": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsChangeSystemTime": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreateGlobalObjects": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreatePageFile": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreatePermanentSharedObjects": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreateSymbolicLinks": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreateToken": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsDebugPrograms": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsRemoteDesktopServicesLogOn": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsDelegation": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsGenerateSecurityAudits": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsImpersonateClient": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsIncreaseSchedulingPriority": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsLoadUnloadDrivers": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsLockMemory": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsManageAuditingAndSecurityLogs": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsManageVolumes": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsModifyFirmwareEnvironment": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsModifyObjectLabels": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsProfileSingleProcess": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsRemoteShutdown": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsRestoreData": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsTakeOwnership": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "xboxServicesEnableXboxGameSaveTask": "Boolean",
  "xboxServicesAccessoryManagementServiceStartupMode": "String",
  "xboxServicesLiveAuthManagerServiceStartupMode": "String",
  "xboxServicesLiveGameSaveServiceStartupMode": "String",
  "xboxServicesLiveNetworkingServiceStartupMode": "String",
  "localSecurityOptionsBlockMicrosoftAccounts": "Boolean",
  "localSecurityOptionsBlockRemoteLogonWithBlankPassword": "Boolean",
  "localSecurityOptionsDisableAdministratorAccount": "Boolean",
  "localSecurityOptionsAdministratorAccountName": "String",
  "localSecurityOptionsDisableGuestAccount": "Boolean",
  "localSecurityOptionsGuestAccountName": "String",
  "localSecurityOptionsAllowUndockWithoutHavingToLogon": "Boolean",
  "localSecurityOptionsBlockUsersInstallingPrinterDrivers": "Boolean",
  "localSecurityOptionsBlockRemoteOpticalDriveAccess": "Boolean",
  "localSecurityOptionsFormatAndEjectOfRemovableMediaAllowedUser": "String",
  "localSecurityOptionsMachineInactivityLimit": "Integer",
  "localSecurityOptionsMachineInactivityLimitInMinutes": "Integer",
  "localSecurityOptionsDoNotRequireCtrlAltDel": "Boolean",
  "localSecurityOptionsHideLastSignedInUser": "Boolean",
  "localSecurityOptionsHideUsernameAtSignIn": "Boolean",
  "localSecurityOptionsLogOnMessageTitle": "String",
  "localSecurityOptionsLogOnMessageText": "String",
  "localSecurityOptionsAllowPKU2UAuthenticationRequests": "Boolean",
  "localSecurityOptionsAllowRemoteCallsToSecurityAccountsManagerHelperBool": "Boolean",
  "localSecurityOptionsAllowRemoteCallsToSecurityAccountsManager": "String",
  "localSecurityOptionsMinimumSessionSecurityForNtlmSspBasedClients": "String",
  "localSecurityOptionsMinimumSessionSecurityForNtlmSspBasedServers": "String",
  "lanManagerAuthenticationLevel": "String",
  "lanManagerWorkstationDisableInsecureGuestLogons": "Boolean",
  "localSecurityOptionsClearVirtualMemoryPageFile": "Boolean",
  "localSecurityOptionsAllowSystemToBeShutDownWithoutHavingToLogOn": "Boolean",
  "localSecurityOptionsAllowUIAccessApplicationElevation": "Boolean",
  "localSecurityOptionsVirtualizeFileAndRegistryWriteFailuresToPerUserLocations": "Boolean",
  "localSecurityOptionsOnlyElevateSignedExecutables": "Boolean",
  "localSecurityOptionsAdministratorElevationPromptBehavior": "String",
  "localSecurityOptionsStandardUserElevationPromptBehavior": "String",
  "localSecurityOptionsSwitchToSecureDesktopWhenPromptingForElevation": "Boolean",
  "localSecurityOptionsDetectApplicationInstallationsAndPromptForElevation": "Boolean",
  "localSecurityOptionsAllowUIAccessApplicationsForSecureLocations": "Boolean",
  "localSecurityOptionsUseAdminApprovalMode": "Boolean",
  "localSecurityOptionsUseAdminApprovalModeForAdministrators": "Boolean",
  "localSecurityOptionsInformationShownOnLockScreen": "String",
  "localSecurityOptionsInformationDisplayedOnLockScreen": "String",
  "localSecurityOptionsDisableClientDigitallySignCommunicationsIfServerAgrees": "Boolean",
  "localSecurityOptionsClientDigitallySignCommunicationsAlways": "Boolean",
  "localSecurityOptionsClientSendUnencryptedPasswordToThirdPartySMBServers": "Boolean",
  "localSecurityOptionsDisableServerDigitallySignCommunicationsAlways": "Boolean",
  "localSecurityOptionsDisableServerDigitallySignCommunicationsIfClientAgrees": "Boolean",
  "localSecurityOptionsRestrictAnonymousAccessToNamedPipesAndShares": "Boolean",
  "localSecurityOptionsDoNotAllowAnonymousEnumerationOfSAMAccounts": "Boolean",
  "localSecurityOptionsAllowAnonymousEnumerationOfSAMAccountsAndShares": "Boolean",
  "localSecurityOptionsDoNotStoreLANManagerHashValueOnNextPasswordChange": "Boolean",
  "localSecurityOptionsSmartCardRemovalBehavior": "String",
  "defenderSecurityCenterDisableAppBrowserUI": "Boolean",
  "defenderSecurityCenterDisableFamilyUI": "Boolean",
  "defenderSecurityCenterDisableHealthUI": "Boolean",
  "defenderSecurityCenterDisableNetworkUI": "Boolean",
  "defenderSecurityCenterDisableVirusUI": "Boolean",
  "defenderSecurityCenterDisableAccountUI": "Boolean",
  "defenderSecurityCenterDisableClearTpmUI": "Boolean",
  "defenderSecurityCenterDisableHardwareUI": "Boolean",
  "defenderSecurityCenterDisableNotificationAreaUI": "Boolean",
  "defenderSecurityCenterDisableRansomwareUI": "Boolean",
  "defenderSecurityCenterDisableSecureBootUI": "Boolean",
  "defenderSecurityCenterDisableTroubleshootingUI": "Boolean",
  "defenderSecurityCenterDisableVulnerableTpmFirmwareUpdateUI": "Boolean",
  "defenderSecurityCenterOrganizationDisplayName": "String",
  "defenderSecurityCenterHelpEmail": "String",
  "defenderSecurityCenterHelpPhone": "String",
  "defenderSecurityCenterHelpURL": "String",
  "defenderSecurityCenterNotificationsFromApp": "String",
  "defenderSecurityCenterITContactDisplay": "String",
  "windowsDefenderTamperProtection": "String",
  "firewallBlockStatefulFTP": "Boolean",
  "firewallIdleTimeoutForSecurityAssociationInSeconds": "Integer",
  "firewallPreSharedKeyEncodingMethod": "String",
  "firewallIPSecExemptionsNone": "Boolean",
  "firewallIPSecExemptionsAllowNeighborDiscovery": "Boolean",
  "firewallIPSecExemptionsAllowICMP": "Boolean",
  "firewallIPSecExemptionsAllowRouterDiscovery": "Boolean",
  "firewallIPSecExemptionsAllowDHCP": "Boolean",
  "firewallCertificateRevocationListCheckMethod": "String",
  "firewallMergeKeyingModuleSettings": "Boolean",
  "firewallPacketQueueingMethod": "String",
  "firewallProfileDomain": {
    "@odata.type": "microsoft.graph.windowsFirewallNetworkProfile"
  },
  "firewallProfilePublic": {
    "@odata.type": "microsoft.graph.windowsFirewallNetworkProfile"
  },
  "firewallProfilePrivate": {
    "@odata.type": "microsoft.graph.windowsFirewallNetworkProfile"
  },
  "defenderAdobeReaderLaunchChildProcess": "String",
  "defenderAttackSurfaceReductionExcludedPaths": [
    "String"
  ],
  "defenderOfficeAppsOtherProcessInjectionType": "String",
  "defenderOfficeAppsOtherProcessInjection": "String",
  "defenderOfficeCommunicationAppsLaunchChildProcess": "String",
  "defenderOfficeAppsExecutableContentCreationOrLaunchType": "String",
  "defenderOfficeAppsExecutableContentCreationOrLaunch": "String",
  "defenderOfficeAppsLaunchChildProcessType": "String",
  "defenderOfficeAppsLaunchChildProcess": "String",
  "defenderOfficeMacroCodeAllowWin32ImportsType": "String",
  "defenderOfficeMacroCodeAllowWin32Imports": "String",
  "defenderScriptObfuscatedMacroCodeType": "String",
  "defenderScriptObfuscatedMacroCode": "String",
  "defenderScriptDownloadedPayloadExecutionType": "String",
  "defenderScriptDownloadedPayloadExecution": "String",
  "defenderPreventCredentialStealingType": "String",
  "defenderProcessCreationType": "String",
  "defenderProcessCreation": "String",
  "defenderUntrustedUSBProcessType": "String",
  "defenderUntrustedUSBProcess": "String",
  "defenderUntrustedExecutableType": "String",
  "defenderUntrustedExecutable": "String",
  "defenderEmailContentExecutionType": "String",
  "defenderEmailContentExecution": "String",
  "defenderAdvancedRansomewareProtectionType": "String",
  "defenderGuardMyFoldersType": "String",
  "defenderGuardedFoldersAllowedAppPaths": [
    "String"
  ],
  "defenderAdditionalGuardedFolders": [
    "String"
  ],
  "defenderNetworkProtectionType": "String",
  "defenderExploitProtectionXml": "Binary",
  "defenderExploitProtectionXmlFileName": "String",
  "defenderSecurityCenterBlockExploitProtectionOverride": "Boolean",
  "appLockerApplicationControl": "String",
  "deviceGuardLocalSystemAuthorityCredentialGuardSettings": "String",
  "deviceGuardEnableVirtualizationBasedSecurity": "Boolean",
  "deviceGuardEnableSecureBootWithDMA": "Boolean",
  "deviceGuardSecureBootWithDMA": "String",
  "deviceGuardLaunchSystemGuard": "String",
  "smartScreenEnableInShell": "Boolean",
  "smartScreenBlockOverrideForFiles": "Boolean",
  "applicationGuardEnabled": "Boolean",
  "applicationGuardEnabledOptions": "String",
  "applicationGuardBlockFileTransfer": "String",
  "applicationGuardBlockNonEnterpriseContent": "Boolean",
  "applicationGuardAllowPersistence": "Boolean",
  "applicationGuardForceAuditing": "Boolean",
  "applicationGuardBlockClipboardSharing": "String",
  "applicationGuardAllowPrintToPDF": "Boolean",
  "applicationGuardAllowPrintToXPS": "Boolean",
  "applicationGuardAllowPrintToLocalPrinters": "Boolean",
  "applicationGuardAllowPrintToNetworkPrinters": "Boolean",
  "applicationGuardAllowVirtualGPU": "Boolean",
  "applicationGuardAllowFileSaveOnHost": "Boolean",
  "bitLockerAllowStandardUserEncryption": "Boolean",
  "bitLockerDisableWarningForOtherDiskEncryption": "Boolean",
  "bitLockerEnableStorageCardEncryptionOnMobile": "Boolean",
  "bitLockerEncryptDevice": "Boolean",
  "bitLockerSystemDrivePolicy": {
    "@odata.type": "microsoft.graph.bitLockerSystemDrivePolicy"
  },
  "bitLockerFixedDrivePolicy": {
    "@odata.type": "microsoft.graph.bitLockerFixedDrivePolicy"
  },
  "bitLockerRemovableDrivePolicy": {
    "@odata.type": "microsoft.graph.bitLockerRemovableDrivePolicy"
  },
  "bitLockerRecoveryPasswordRotation": "String",
  "defenderDisableScanArchiveFiles": "Boolean",
  "defenderAllowScanArchiveFiles": "Boolean",
  "defenderDisableBehaviorMonitoring": "Boolean",
  "defenderAllowBehaviorMonitoring": "Boolean",
  "defenderDisableCloudProtection": "Boolean",
  "defenderAllowCloudProtection": "Boolean",
  "defenderEnableScanIncomingMail": "Boolean",
  "defenderEnableScanMappedNetworkDrivesDuringFullScan": "Boolean",
  "defenderDisableScanRemovableDrivesDuringFullScan": "Boolean",
  "defenderAllowScanRemovableDrivesDuringFullScan": "Boolean",
  "defenderDisableScanDownloads": "Boolean",
  "defenderAllowScanDownloads": "Boolean",
  "defenderDisableIntrusionPreventionSystem": "Boolean",
  "defenderAllowIntrusionPreventionSystem": "Boolean",
  "defenderDisableOnAccessProtection": "Boolean",
  "defenderAllowOnAccessProtection": "Boolean",
  "defenderDisableRealTimeMonitoring": "Boolean",
  "defenderAllowRealTimeMonitoring": "Boolean",
  "defenderDisableScanNetworkFiles": "Boolean",
  "defenderAllowScanNetworkFiles": "Boolean",
  "defenderDisableScanScriptsLoadedInInternetExplorer": "Boolean",
  "defenderAllowScanScriptsLoadedInInternetExplorer": "Boolean",
  "defenderBlockEndUserAccess": "Boolean",
  "defenderAllowEndUserAccess": "Boolean",
  "defenderScanMaxCpuPercentage": "Integer",
  "defenderCheckForSignaturesBeforeRunningScan": "Boolean",
  "defenderCloudBlockLevel": "String",
  "defenderCloudExtendedTimeoutInSeconds": "Integer",
  "defenderDaysBeforeDeletingQuarantinedMalware": "Integer",
  "defenderDisableCatchupFullScan": "Boolean",
  "defenderDisableCatchupQuickScan": "Boolean",
  "defenderEnableLowCpuPriority": "Boolean",
  "defenderFileExtensionsToExclude": [
    "String"
  ],
  "defenderFilesAndFoldersToExclude": [
    "String"
  ],
  "defenderProcessesToExclude": [
    "String"
  ],
  "defenderPotentiallyUnwantedAppAction": "String",
  "defenderScanDirection": "String",
  "defenderScanType": "String",
  "defenderScheduledQuickScanTime": "String (time of day)",
  "defenderScheduledScanDay": "String",
  "defenderScheduledScanTime": "String (time of day)",
  "defenderSignatureUpdateIntervalInHours": "Integer",
  "defenderSubmitSamplesConsentType": "String",
  "defenderDetectedMalwareActions": {
    "@odata.type": "microsoft.graph.defenderDetectedMalwareActions"
  }
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.windows10EndpointProtectionConfiguration",
  "id": "0d00c540-c540-0d00-40c5-000d40c5000d",
  "lastModifiedDateTime": "String (timestamp)",
  "roleScopeTagIds": [
    "String"
  ],
  "supportsScopeTags": "Boolean",
  "deviceManagementApplicabilityRuleOsEdition": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition"
  },
  "deviceManagementApplicabilityRuleOsVersion": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion"
  },
  "deviceManagementApplicabilityRuleDeviceMode": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode"
  },
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "version": "Integer",
  "dmaGuardDeviceEnumerationPolicy": "String",
  "firewallRules": [
    {
      "@odata.type": "microsoft.graph.windowsFirewallRule"
    }
  ],
  "userRightsAccessCredentialManagerAsTrustedCaller": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsAllowAccessFromNetwork": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsBlockAccessFromNetwork": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsActAsPartOfTheOperatingSystem": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsLocalLogOn": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsDenyLocalLogOn": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsBackupData": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsChangeSystemTime": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreateGlobalObjects": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreatePageFile": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreatePermanentSharedObjects": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreateSymbolicLinks": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsCreateToken": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsDebugPrograms": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsRemoteDesktopServicesLogOn": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsDelegation": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsGenerateSecurityAudits": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsImpersonateClient": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsIncreaseSchedulingPriority": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsLoadUnloadDrivers": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsLockMemory": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsManageAuditingAndSecurityLogs": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsManageVolumes": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsModifyFirmwareEnvironment": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsModifyObjectLabels": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsProfileSingleProcess": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsRemoteShutdown": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsRestoreData": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "userRightsTakeOwnership": {
    "@odata.type": "microsoft.graph.deviceManagementUserRightsSetting"
  },
  "xboxServicesEnableXboxGameSaveTask": "Boolean",
  "xboxServicesAccessoryManagementServiceStartupMode": "String",
  "xboxServicesLiveAuthManagerServiceStartupMode": "String",
  "xboxServicesLiveGameSaveServiceStartupMode": "String",
  "xboxServicesLiveNetworkingServiceStartupMode": "String",
  "localSecurityOptionsBlockMicrosoftAccounts": "Boolean",
  "localSecurityOptionsBlockRemoteLogonWithBlankPassword": "Boolean",
  "localSecurityOptionsDisableAdministratorAccount": "Boolean",
  "localSecurityOptionsAdministratorAccountName": "String",
  "localSecurityOptionsDisableGuestAccount": "Boolean",
  "localSecurityOptionsGuestAccountName": "String",
  "localSecurityOptionsAllowUndockWithoutHavingToLogon": "Boolean",
  "localSecurityOptionsBlockUsersInstallingPrinterDrivers": "Boolean",
  "localSecurityOptionsBlockRemoteOpticalDriveAccess": "Boolean",
  "localSecurityOptionsFormatAndEjectOfRemovableMediaAllowedUser": "String",
  "localSecurityOptionsMachineInactivityLimit": "Integer",
  "localSecurityOptionsMachineInactivityLimitInMinutes": "Integer",
  "localSecurityOptionsDoNotRequireCtrlAltDel": "Boolean",
  "localSecurityOptionsHideLastSignedInUser": "Boolean",
  "localSecurityOptionsHideUsernameAtSignIn": "Boolean",
  "localSecurityOptionsLogOnMessageTitle": "String",
  "localSecurityOptionsLogOnMessageText": "String",
  "localSecurityOptionsAllowPKU2UAuthenticationRequests": "Boolean",
  "localSecurityOptionsAllowRemoteCallsToSecurityAccountsManagerHelperBool": "Boolean",
  "localSecurityOptionsAllowRemoteCallsToSecurityAccountsManager": "String",
  "localSecurityOptionsMinimumSessionSecurityForNtlmSspBasedClients": "String",
  "localSecurityOptionsMinimumSessionSecurityForNtlmSspBasedServers": "String",
  "lanManagerAuthenticationLevel": "String",
  "lanManagerWorkstationDisableInsecureGuestLogons": "Boolean",
  "localSecurityOptionsClearVirtualMemoryPageFile": "Boolean",
  "localSecurityOptionsAllowSystemToBeShutDownWithoutHavingToLogOn": "Boolean",
  "localSecurityOptionsAllowUIAccessApplicationElevation": "Boolean",
  "localSecurityOptionsVirtualizeFileAndRegistryWriteFailuresToPerUserLocations": "Boolean",
  "localSecurityOptionsOnlyElevateSignedExecutables": "Boolean",
  "localSecurityOptionsAdministratorElevationPromptBehavior": "String",
  "localSecurityOptionsStandardUserElevationPromptBehavior": "String",
  "localSecurityOptionsSwitchToSecureDesktopWhenPromptingForElevation": "Boolean",
  "localSecurityOptionsDetectApplicationInstallationsAndPromptForElevation": "Boolean",
  "localSecurityOptionsAllowUIAccessApplicationsForSecureLocations": "Boolean",
  "localSecurityOptionsUseAdminApprovalMode": "Boolean",
  "localSecurityOptionsUseAdminApprovalModeForAdministrators": "Boolean",
  "localSecurityOptionsInformationShownOnLockScreen": "String",
  "localSecurityOptionsInformationDisplayedOnLockScreen": "String",
  "localSecurityOptionsDisableClientDigitallySignCommunicationsIfServerAgrees": "Boolean",
  "localSecurityOptionsClientDigitallySignCommunicationsAlways": "Boolean",
  "localSecurityOptionsClientSendUnencryptedPasswordToThirdPartySMBServers": "Boolean",
  "localSecurityOptionsDisableServerDigitallySignCommunicationsAlways": "Boolean",
  "localSecurityOptionsDisableServerDigitallySignCommunicationsIfClientAgrees": "Boolean",
  "localSecurityOptionsRestrictAnonymousAccessToNamedPipesAndShares": "Boolean",
  "localSecurityOptionsDoNotAllowAnonymousEnumerationOfSAMAccounts": "Boolean",
  "localSecurityOptionsAllowAnonymousEnumerationOfSAMAccountsAndShares": "Boolean",
  "localSecurityOptionsDoNotStoreLANManagerHashValueOnNextPasswordChange": "Boolean",
  "localSecurityOptionsSmartCardRemovalBehavior": "String",
  "defenderSecurityCenterDisableAppBrowserUI": "Boolean",
  "defenderSecurityCenterDisableFamilyUI": "Boolean",
  "defenderSecurityCenterDisableHealthUI": "Boolean",
  "defenderSecurityCenterDisableNetworkUI": "Boolean",
  "defenderSecurityCenterDisableVirusUI": "Boolean",
  "defenderSecurityCenterDisableAccountUI": "Boolean",
  "defenderSecurityCenterDisableClearTpmUI": "Boolean",
  "defenderSecurityCenterDisableHardwareUI": "Boolean",
  "defenderSecurityCenterDisableNotificationAreaUI": "Boolean",
  "defenderSecurityCenterDisableRansomwareUI": "Boolean",
  "defenderSecurityCenterDisableSecureBootUI": "Boolean",
  "defenderSecurityCenterDisableTroubleshootingUI": "Boolean",
  "defenderSecurityCenterDisableVulnerableTpmFirmwareUpdateUI": "Boolean",
  "defenderSecurityCenterOrganizationDisplayName": "String",
  "defenderSecurityCenterHelpEmail": "String",
  "defenderSecurityCenterHelpPhone": "String",
  "defenderSecurityCenterHelpURL": "String",
  "defenderSecurityCenterNotificationsFromApp": "String",
  "defenderSecurityCenterITContactDisplay": "String",
  "windowsDefenderTamperProtection": "String",
  "firewallBlockStatefulFTP": "Boolean",
  "firewallIdleTimeoutForSecurityAssociationInSeconds": "Integer",
  "firewallPreSharedKeyEncodingMethod": "String",
  "firewallIPSecExemptionsNone": "Boolean",
  "firewallIPSecExemptionsAllowNeighborDiscovery": "Boolean",
  "firewallIPSecExemptionsAllowICMP": "Boolean",
  "firewallIPSecExemptionsAllowRouterDiscovery": "Boolean",
  "firewallIPSecExemptionsAllowDHCP": "Boolean",
  "firewallCertificateRevocationListCheckMethod": "String",
  "firewallMergeKeyingModuleSettings": "Boolean",
  "firewallPacketQueueingMethod": "String",
  "firewallProfileDomain": {
    "@odata.type": "microsoft.graph.windowsFirewallNetworkProfile"
  },
  "firewallProfilePublic": {
    "@odata.type": "microsoft.graph.windowsFirewallNetworkProfile"
  },
  "firewallProfilePrivate": {
    "@odata.type": "microsoft.graph.windowsFirewallNetworkProfile"
  },
  "defenderAdobeReaderLaunchChildProcess": "String",
  "defenderAttackSurfaceReductionExcludedPaths": [
    "String"
  ],
  "defenderOfficeAppsOtherProcessInjectionType": "String",
  "defenderOfficeAppsOtherProcessInjection": "String",
  "defenderOfficeCommunicationAppsLaunchChildProcess": "String",
  "defenderOfficeAppsExecutableContentCreationOrLaunchType": "String",
  "defenderOfficeAppsExecutableContentCreationOrLaunch": "String",
  "defenderOfficeAppsLaunchChildProcessType": "String",
  "defenderOfficeAppsLaunchChildProcess": "String",
  "defenderOfficeMacroCodeAllowWin32ImportsType": "String",
  "defenderOfficeMacroCodeAllowWin32Imports": "String",
  "defenderScriptObfuscatedMacroCodeType": "String",
  "defenderScriptObfuscatedMacroCode": "String",
  "defenderScriptDownloadedPayloadExecutionType": "String",
  "defenderScriptDownloadedPayloadExecution": "String",
  "defenderPreventCredentialStealingType": "String",
  "defenderProcessCreationType": "String",
  "defenderProcessCreation": "String",
  "defenderUntrustedUSBProcessType": "String",
  "defenderUntrustedUSBProcess": "String",
  "defenderUntrustedExecutableType": "String",
  "defenderUntrustedExecutable": "String",
  "defenderEmailContentExecutionType": "String",
  "defenderEmailContentExecution": "String",
  "defenderAdvancedRansomewareProtectionType": "String",
  "defenderGuardMyFoldersType": "String",
  "defenderGuardedFoldersAllowedAppPaths": [
    "String"
  ],
  "defenderAdditionalGuardedFolders": [
    "String"
  ],
  "defenderNetworkProtectionType": "String",
  "defenderExploitProtectionXml": "Binary",
  "defenderExploitProtectionXmlFileName": "String",
  "defenderSecurityCenterBlockExploitProtectionOverride": "Boolean",
  "appLockerApplicationControl": "String",
  "deviceGuardLocalSystemAuthorityCredentialGuardSettings": "String",
  "deviceGuardEnableVirtualizationBasedSecurity": "Boolean",
  "deviceGuardEnableSecureBootWithDMA": "Boolean",
  "deviceGuardSecureBootWithDMA": "String",
  "deviceGuardLaunchSystemGuard": "String",
  "smartScreenEnableInShell": "Boolean",
  "smartScreenBlockOverrideForFiles": "Boolean",
  "applicationGuardEnabled": "Boolean",
  "applicationGuardEnabledOptions": "String",
  "applicationGuardBlockFileTransfer": "String",
  "applicationGuardBlockNonEnterpriseContent": "Boolean",
  "applicationGuardAllowPersistence": "Boolean",
  "applicationGuardForceAuditing": "Boolean",
  "applicationGuardBlockClipboardSharing": "String",
  "applicationGuardAllowPrintToPDF": "Boolean",
  "applicationGuardAllowPrintToXPS": "Boolean",
  "applicationGuardAllowPrintToLocalPrinters": "Boolean",
  "applicationGuardAllowPrintToNetworkPrinters": "Boolean",
  "applicationGuardAllowVirtualGPU": "Boolean",
  "applicationGuardAllowFileSaveOnHost": "Boolean",
  "bitLockerAllowStandardUserEncryption": "Boolean",
  "bitLockerDisableWarningForOtherDiskEncryption": "Boolean",
  "bitLockerEnableStorageCardEncryptionOnMobile": "Boolean",
  "bitLockerEncryptDevice": "Boolean",
  "bitLockerSystemDrivePolicy": {
    "@odata.type": "microsoft.graph.bitLockerSystemDrivePolicy"
  },
  "bitLockerFixedDrivePolicy": {
    "@odata.type": "microsoft.graph.bitLockerFixedDrivePolicy"
  },
  "bitLockerRemovableDrivePolicy": {
    "@odata.type": "microsoft.graph.bitLockerRemovableDrivePolicy"
  },
  "bitLockerRecoveryPasswordRotation": "String",
  "defenderDisableScanArchiveFiles": "Boolean",
  "defenderAllowScanArchiveFiles": "Boolean",
  "defenderDisableBehaviorMonitoring": "Boolean",
  "defenderAllowBehaviorMonitoring": "Boolean",
  "defenderDisableCloudProtection": "Boolean",
  "defenderAllowCloudProtection": "Boolean",
  "defenderEnableScanIncomingMail": "Boolean",
  "defenderEnableScanMappedNetworkDrivesDuringFullScan": "Boolean",
  "defenderDisableScanRemovableDrivesDuringFullScan": "Boolean",
  "defenderAllowScanRemovableDrivesDuringFullScan": "Boolean",
  "defenderDisableScanDownloads": "Boolean",
  "defenderAllowScanDownloads": "Boolean",
  "defenderDisableIntrusionPreventionSystem": "Boolean",
  "defenderAllowIntrusionPreventionSystem": "Boolean",
  "defenderDisableOnAccessProtection": "Boolean",
  "defenderAllowOnAccessProtection": "Boolean",
  "defenderDisableRealTimeMonitoring": "Boolean",
  "defenderAllowRealTimeMonitoring": "Boolean",
  "defenderDisableScanNetworkFiles": "Boolean",
  "defenderAllowScanNetworkFiles": "Boolean",
  "defenderDisableScanScriptsLoadedInInternetExplorer": "Boolean",
  "defenderAllowScanScriptsLoadedInInternetExplorer": "Boolean",
  "defenderBlockEndUserAccess": "Boolean",
  "defenderAllowEndUserAccess": "Boolean",
  "defenderScanMaxCpuPercentage": "Integer",
  "defenderCheckForSignaturesBeforeRunningScan": "Boolean",
  "defenderCloudBlockLevel": "String",
  "defenderCloudExtendedTimeoutInSeconds": "Integer",
  "defenderDaysBeforeDeletingQuarantinedMalware": "Integer",
  "defenderDisableCatchupFullScan": "Boolean",
  "defenderDisableCatchupQuickScan": "Boolean",
  "defenderEnableLowCpuPriority": "Boolean",
  "defenderFileExtensionsToExclude": [
    "String"
  ],
  "defenderFilesAndFoldersToExclude": [
    "String"
  ],
  "defenderProcessesToExclude": [
    "String"
  ],
  "defenderPotentiallyUnwantedAppAction": "String",
  "defenderScanDirection": "String",
  "defenderScanType": "String",
  "defenderScheduledQuickScanTime": "String (time of day)",
  "defenderScheduledScanDay": "String",
  "defenderScheduledScanTime": "String (time of day)",
  "defenderSignatureUpdateIntervalInHours": "Integer",
  "defenderSubmitSamplesConsentType": "String",
  "defenderDetectedMalwareActions": {
    "@odata.type": "microsoft.graph.defenderDetectedMalwareActions"
  }
}
```

