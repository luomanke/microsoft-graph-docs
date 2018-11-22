---

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Device Compilance Policy Setting State summary across the account.
## Methods
|Method|Return Type|Description|
|:---|:---|:---|
|[List deviceCompliancePolicySettingStateSummaries](../api/intune-deviceconfig-devicecompliancepolicysettingstatesummary-list.md)|[deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md) collection|List properties and relationships of the [deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md) objects.|
|[Get deviceCompliancePolicySettingStateSummary](../api/intune-deviceconfig-devicecompliancepolicysettingstatesummary-get.md)|[deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md)|Read properties and relationships of the [deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md) object.|
|[Create deviceCompliancePolicySettingStateSummary](../api/intune-deviceconfig-devicecompliancepolicysettingstatesummary-create.md)|[deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md)|Create a new [deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md) object.|
|[Delete deviceCompliancePolicySettingStateSummary](../api/intune-deviceconfig-devicecompliancepolicysettingstatesummary-delete.md)|None|Deletes a [deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md).|
|[Update deviceCompliancePolicySettingStateSummary](../api/intune-deviceconfig-devicecompliancepolicysettingstatesummary-update.md)|[deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md)|Update the properties of a [deviceCompliancePolicySettingStateSummary](../resources/intune-deviceconfig-devicecompliancepolicysettingstatesummary.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity.|
|setting|String|The setting class name and property name.|
|settingName|String|Name of the setting.|
|platformType|[policyPlatformType](../resources/intune-deviceconfig-policyplatformtype.md)|Setting platform. Possible values are: `android`, `androidForWork`, `iOS`, `macOS`, `windowsPhone81`, `windows81AndLater`, `windows10AndLater`, `androidWorkProfile`, `all`.|
|unknownDeviceCount|Int32|Number of unknown devices|
|notApplicableDeviceCount|Int32|Number of not applicable devices|
|compliantDeviceCount|Int32|Number of compliant devices|
|remediatedDeviceCount|Int32|Number of remediated devices|
|nonCompliantDeviceCount|Int32|Number of NonCompliant devices|
|errorDeviceCount|Int32|Number of error devices|
|conflictDeviceCount|Int32|Number of conflict devices|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|deviceComplianceSettingStates|[deviceComplianceSettingState](../resources/intune-deviceconfig-devicecompliancesettingstate.md) collection|Not yet documented|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceCompliancePolicySettingStateSummary"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceCompliancePolicySettingStateSummary",
  "id": "String (identifier)",
  "setting": "String",
  "settingName": "String",
  "platformType": "String",
  "unknownDeviceCount": 1024,
  "notApplicableDeviceCount": 1024,
  "compliantDeviceCount": 1024,
  "remediatedDeviceCount": 1024,
  "nonCompliantDeviceCount": 1024,
  "errorDeviceCount": 1024,
  "conflictDeviceCount": 1024
}
```




