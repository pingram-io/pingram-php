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
**account_id** | **string** | Account id, for ACCOUNT_USAGE. | [optional]
**year_month_day** | **string** | Billing period start (YYYY-MM-DD), for ACCOUNT_USAGE. | [optional]
**resets_on** | **string** | Date the monthly budget resets (YYYY-MM-DD), for ACCOUNT_USAGE. | [optional]
**percent** | **float** | Whole percent of the monthly budget used, for ACCOUNT_USAGE. | [optional]
**spent** | **float** | Amount spent against the monthly budget, for ACCOUNT_USAGE. | [optional]
**cost_cap** | **float** | Monthly budget the percent was measured against, for ACCOUNT_USAGE. | [optional]
**auto_upgrade** | **bool** | Whether the account raises its budget automatically, for ACCOUNT_USAGE. | [optional]
**usage** | [**array<string,\Pingram\Model\WebhookEventUsageValue>**](WebhookEventUsageValue.md) | Per-channel volume and cost for the current period, for ACCOUNT_USAGE. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
