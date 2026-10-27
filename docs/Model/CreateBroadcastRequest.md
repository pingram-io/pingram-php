# # CreateBroadcastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  |
**type** | **string** | Notification type id. Optional on create; required before send/schedule. Created on the fly when missing. | [optional]
**channel** | **string** |  | [optional]
**audience** | [**\Pingram\Model\BroadcastResponseAudience**](BroadcastResponseAudience.md) |  |
**from_name** | **string** |  |
**from_address** | **string** | From address. Use an address on a domain verified for this account to email other people. The shared address &#x60;noreply@pingram.io&#x60; can send a test broadcast only to your own account email as the sole recipient. Verify a domain to send to a wider audience. |
**reply_to_address** | **string** |  | [optional]
**subject** | **string** |  |
**html** | **string** |  |
**internal_template** | **string** | Optional visual-editor source. Pair with html. A later update can add it to a draft by sending it with html. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
