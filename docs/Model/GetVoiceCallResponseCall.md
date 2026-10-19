# # GetVoiceCallResponseCall

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tracking_id** | **string** |  |
**status** | **string** |  |
**config_name** | **string** |  |
**direction** | **string** |  |
**source** | **string** |  |
**from** | **string** |  |
**to** | **string** |  |
**started_at** | **string** |  |
**answered_at** | **string** | Set when the callee answers. Absent while the phone is still ringing. | [optional]
**duration_seconds** | **float** |  |
**outcome** | **string** |  | [optional]
**end_reason** | **string** | Machine-readable reason the call ended — persisted on every call record. | [optional]
**end_detail** | **string** | Short human-readable detail, such as why the call failed. | [optional]
**timeline** | [**\Pingram\Model\GetVoiceCallResponseCallTimelineInner[]**](GetVoiceCallResponseCallTimelineInner.md) | Full chronological timeline (transcript + ops events). |
**recording_url** | **string** |  | [optional]
**variables** | **array<string,string>** |  | [optional]
**cost** | [**\Pingram\Model\GetVoiceCallResponseCallCost**](GetVoiceCallResponseCallCost.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
