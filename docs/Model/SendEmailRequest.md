# # SendEmailRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | The notification type to send. |
**to** | **string** | The email address of the recipient. |
**subject** | **string** | The subject of the email. |
**html** | **string** | The HTML body of the email. |
**from_name** | **string** | The display name of the sender. | [optional]
**from_address** | **string** | The email address of the sender. | [optional]
**preview_text** | **string** | The preview text of the email. | [optional]
**reply_to_addresses** | **string[]** | The reply-to addresses of the email. | [optional]
**cc_addresses** | **string[]** | The CC addresses of the email. | [optional]
**bcc_addresses** | **string[]** | The BCC addresses of the email. | [optional]
**attachments** | [**\Pingram\Model\SendEmailRequestAttachmentsInner[]**](SendEmailRequestAttachmentsInner.md) | URL-based file attachments. Up to 20 MB per file. | [optional]
**schedule** | **string** | The ISO 8601 datetime to schedule the email. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
