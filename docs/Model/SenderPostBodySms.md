# # SenderPostBodySms

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message** | **string** | SMS/MMS body text. | [optional]
**media_urls** | **string[]** | Public HTTPS URLs of media to attach (MMS). Carriers fetch these via GET. Total size limits apply per provider. | [optional]
**auto_reply** | [**\Pingram\Model\SenderPostBodySmsAutoReply**](SenderPostBodySmsAutoReply.md) |  | [optional]
**from** | **string** | Override the sender phone number. Must be a verified number on your account. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
