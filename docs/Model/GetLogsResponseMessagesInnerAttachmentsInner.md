# # GetLogsResponseMessagesInnerAttachmentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**filename** | **string** | Original filename from the message. |
**content_type** | **string** | MIME type of the file. |
**size** | **float** | Size in bytes. This response does not include the file bytes. |
**content_id** | **string** | Content-ID with angle brackets removed, so it matches &#x60;cid:&#x60; references in &#x60;bodyHtml&#x60;. Omitted when the part has no Content-ID. | [optional]
**content_disposition** | **string** | &#x60;inline&#x60; when the HTML body references this file; &#x60;attachment&#x60; when it is a separate file. Omitted when the message does not say which. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
