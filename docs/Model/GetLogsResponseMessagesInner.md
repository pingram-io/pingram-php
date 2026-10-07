# # GetLogsResponseMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tracking_id** | **string** |  |
**event_type** | **string** |  |
**timestamp** | **string** |  |
**epoch_ms** | **float** |  |
**inbox** | **string** | Address that received the mail. Same value as &#x60;matched.email&#x60; on the EMAIL_INBOUND webhook, including when that address was only in Cc or Bcc. | [optional]
**from** | **string** |  | [optional]
**from_name** | **string** |  | [optional]
**subject** | **string** |  | [optional]
**to** | **string[]** | Original To header addresses. Not the address that received the mail. | [optional]
**cc** | **string[]** | Original Cc header addresses. | [optional]
**bcc** | **string[]** | Bcc header addresses still on the delivered message. Usually omitted, because the Bcc header is removed before delivery. | [optional]
**reply_to** | **string** |  | [optional]
**body_text** | **string** |  | [optional]
**body_html** | **string** |  | [optional]
**attachments** | [**\Pingram\Model\GetLogsResponseMessagesInnerAttachmentsInner[]**](GetLogsResponseMessagesInnerAttachmentsInner.md) |  | [optional]
**media** | [**\Pingram\Model\GetLogsResponseMessagesInnerMediaInner[]**](GetLogsResponseMessagesInnerMediaInner.md) | Inbound MMS attachments (includes contentType when available). | [optional]
**message_id** | **string** |  | [optional]
**in_reply_to** | **string** |  | [optional]
**references** | **string** |  | [optional]
**resolution_type** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
