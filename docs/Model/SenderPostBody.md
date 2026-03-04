# # SenderPostBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notification_id** | **string** |  | [optional]
**user** | [**\Pingram\Model\SenderPostBodyUser**](SenderPostBodyUser.md) |  | [optional]
**merge_tags** | **object** |  | [optional]
**replace** | **array<string,string>** |  | [optional]
**type** | **string** | ID of the notification type (e.g. \&quot;welcome_email\&quot;). Creates a new notification if it does not exist. | [optional]
**to** | [**\Pingram\Model\SenderPostBodyTo**](SenderPostBodyTo.md) |  | [optional]
**force_channels** | [**\Pingram\Model\ChannelsEnum[]**](ChannelsEnum.md) | Override which channels to send to (e.g. [\&quot;EMAIL\&quot;, \&quot;SMS\&quot;]). Bypasses notification channel config. | [optional]
**parameters** | **array<string,mixed>** | Key-value pairs for template merge tags. Replaces placeholders like {{firstName}} in templates. | [optional]
**secondary_id** | **string** | Optional sub-notification identifier for grouping or tracking. | [optional]
**template_id** | **string** | Specific template ID to use. If omitted, uses the default template for each channel. | [optional]
**sub_notification_id** | **string** | Sub-notification identifier (e.g. for grouping related notifications). | [optional]
**options** | [**\Pingram\Model\SenderPostBodyOptions**](SenderPostBodyOptions.md) |  | [optional]
**schedule** | **string** |  | [optional]
**email** | [**\Pingram\Model\SenderPostBodyEmail**](SenderPostBodyEmail.md) |  | [optional]
**inapp** | [**\Pingram\Model\SenderPostBodyInapp**](SenderPostBodyInapp.md) |  | [optional]
**sms** | [**\Pingram\Model\SenderPostBodySms**](SenderPostBodySms.md) |  | [optional]
**call** | [**\Pingram\Model\SenderPostBodyCall**](SenderPostBodyCall.md) |  | [optional]
**web_push** | [**\Pingram\Model\SenderPostBodyWebPush**](SenderPostBodyWebPush.md) |  | [optional]
**mobile_push** | [**\Pingram\Model\SenderPostBodyMobilePush**](SenderPostBodyMobilePush.md) |  | [optional]
**slack** | [**\Pingram\Model\SenderPostBodySlack**](SenderPostBodySlack.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
