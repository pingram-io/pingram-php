# # GetTemplatesListResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**env_id** | **string** |  |
**notification_id** | **string** |  |
**template_id** | **string** |  |
**channel** | [**\Pingram\Model\ChannelsEnum**](ChannelsEnum.md) |  |
**default** | **bool** |  |
**is_default_for** | **array<string,bool>** |  | [optional]
**html** | **string** |  |
**preview_text** | **string** |  | [optional]
**internal** | **string** |  |
**subject** | **string** |  |
**sender_name** | **string** |  |
**sender_email** | **string** |  |
**title** | **string** |  |
**redirect_url** | **string** |  |
**image_url** | **string** |  |
**instant** | [**\Pingram\Model\GetTemplatesListResponseInnerAnyOf1Instant**](GetTemplatesListResponseInnerAnyOf1Instant.md) |  |
**batch** | [**\Pingram\Model\GetTemplatesListResponseInnerAnyOf1Instant**](GetTemplatesListResponseInnerAnyOf1Instant.md) |  |
**text** | **string** |  |
**message** | **string** |  |
**icon** | **string** |  | [optional]
**url** | **string** |  | [optional]
**blocks** | **array<string,object>[]** |  | [optional]
**username** | **string** |  | [optional]
**thread_ts** | **string** |  | [optional]
**reply_broadcast** | **bool** |  | [optional]
**parse** | **string** |  | [optional]
**link_names** | **bool** |  | [optional]
**mrkdwn** | **bool** |  | [optional]
**unfurl_links** | **bool** |  | [optional]
**unfurl_media** | **bool** |  | [optional]
**metadata** | [**\Pingram\Model\GetTemplatesListResponseInnerAnyOf5Metadata**](GetTemplatesListResponseInnerAnyOf5Metadata.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
