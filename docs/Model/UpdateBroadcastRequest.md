# # UpdateBroadcastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional]
**type** | **string** |  | [optional]
**channel** | **string** |  | [optional]
**audience** | [**\Pingram\Model\BroadcastResponseAudience**](BroadcastResponseAudience.md) |  | [optional]
**from_name** | **string** |  | [optional]
**from_address** | **string** |  | [optional]
**reply_to_address** | **string** | Omit to leave unchanged. Empty string clears Reply-To. | [optional]
**subject** | **string** |  | [optional]
**html** | **string** |  | [optional]
**internal_template** | **string** | Optional visual-editor source. Can be updated only when the broadcast was created with it; cannot be added to an html-only broadcast. Pair with html. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
