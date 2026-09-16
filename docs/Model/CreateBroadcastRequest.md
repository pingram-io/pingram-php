# # CreateBroadcastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  |
**type** | **string** | Notification type id. Optional on create; required before send/schedule. Created on the fly when missing. | [optional]
**channel** | **string** |  | [optional]
**audience** | [**\Pingram\Model\BroadcastResponseAudience**](BroadcastResponseAudience.md) |  |
**from_name** | **string** |  |
**from_address** | **string** |  |
**reply_to_address** | **string** |  | [optional]
**subject** | **string** |  |
**html** | **string** |  |
**internal_template** | **string** | Optional visual-editor source. Can only be set at create time and must stay paired with html. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
