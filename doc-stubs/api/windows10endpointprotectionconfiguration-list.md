---
title: "List windows10EndpointProtectionConfiguration"
description: "Get a list of the windows10EndpointProtectionConfiguration objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List windows10EndpointProtectionConfiguration
Namespace: microsoft.graph

Get a list of the [windows10EndpointProtectionConfiguration](../resources/windows10endpointprotectionconfiguration.md) objects and their properties.

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
GET ** Collection URI for microsoft.graph.windows10EndpointProtectionConfiguration not found
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [windows10EndpointProtectionConfiguration](../resources/windows10endpointprotectionconfiguration.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_windows10endpointprotectionconfiguration"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for microsoft.graph.windows10EndpointProtectionConfiguration not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.windows10EndpointProtectionConfiguration)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
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
  ]
}
```

