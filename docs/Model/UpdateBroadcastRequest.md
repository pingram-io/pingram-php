# # UpdateBroadcastRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [optional]
**type** | **string** |  | [optional]
**channel** | **string** |  | [optional]
**audience** | [**\Pingram\Model\BroadcastResponseAudience**](BroadcastResponseAudience.md) |  | [optional]
**from_name** | **string** |  | [optional]
**from_address** | **string** | From address. Use an address on a domain verified for this account to email other people. The shared address &#x60;noreply@pingram.io&#x60; can send a test broadcast only to your own account email as the sole recipient. Verify a domain to send to a wider audience. | [optional]
**reply_to_address** | **string** | Omit to leave unchanged. Empty string clears Reply-To. | [optional]
**subject** | **string** |  | [optional]
**html** | **string** |  | [optional]
**internal_template** | **string** | Visual-editor source. Send with html to add it to an html-only draft or to update it. Cannot be removed. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
