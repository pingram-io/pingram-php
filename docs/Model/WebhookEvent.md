# # WebhookEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_type** | **string** |  |
**channel** | [**\Pingram\Model\ChannelsEnum**](ChannelsEnum.md) |  |
**user_id** | **string** | User ID the notification was sent to. |
**notification_id** | **string** | Notification type ID. |
**tracking_id** | **string** | Unique tracking ID for this notification instance. |
**failure_code** | **string** | Failure code for *_FAILED events. | [optional]
**clicked_link** | **string** | Clicked URL for EMAIL_CLICK events. | [optional]
**clicked_link_tags** | **array<string,string[]>** | Link tags for EMAIL_CLICK events. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
