# # SendGroupTextRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Notification type you can use later for filtering, analytics, and more. For example, \&quot;onboarding\&quot; or \&quot;threshold_alert\&quot;. |
**to** | **string[]** | Two to eight mobile numbers in the US or Canada. Each number is billed at the multimedia message rate, including a text with no attachment. |
**message** | **string** | Text to send. Required when mediaUrls is omitted. | [optional]
**subject** | **string** | Subject shown with the group text. Optional. | [optional]
**media_urls** | **string[]** | Public HTTPS URLs of pictures or files to attach. | [optional]
**from** | **string** | Number the group text is sent from. When omitted, a number on this account is used. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
