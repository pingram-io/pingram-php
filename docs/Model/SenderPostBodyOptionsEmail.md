# # SenderPostBodyOptionsEmail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reply_to_addresses** | **string[]** | Reply-to addresses for the email. | [optional]
**cc_addresses** | **string[]** | CC recipients. | [optional]
**bcc_addresses** | **string[]** | BCC recipients. | [optional]
**from_address** | **string** | Override sender email address. | [optional]
**from_name** | **string** | Override sender display name. | [optional]
**attachments** | [**\Pingram\Model\SenderPostBodyOptionsEmailAttachmentsInner[]**](SenderPostBodyOptionsEmailAttachmentsInner.md) | File attachments (by URL or inline base64 content). Inline &#x60;content&#x60;: ~4 MB raw per file (413 if exceeded). URL &#x60;url&#x60;: up to 20 MB per file. | [optional]
**condition** | **string** | Conditional expression for when to send (e.g. merge tag logic). | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
