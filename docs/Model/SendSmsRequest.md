# # SendSmsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | The notification type to send. |
**to** | **string** | The phone number of the recipient. |
**message** | **string** | The message of the SMS or MMS notification. Optional when &#x60;mediaUrls&#x60; is provided. | [optional]
**media_urls** | **string[]** | Public HTTPS URLs of media to attach (MMS). | [optional]
**schedule** | **string** | The ISO 8601 datetime to schedule the SMS notification. | [optional]
**from** | **string** | Override the sender phone number. Must be a dedicated number on your Pingram account. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
