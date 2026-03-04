# # SenderPostBodySlack

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Fallback plain text (required when using blocks). |
**blocks** | **array<string,mixed>[]** | Slack Block Kit blocks. | [optional]
**username** | **string** | Override bot username. | [optional]
**icon** | **string** | Icon: emoji (e.g. \&quot;:smile:\&quot;) or URL. Default: bot&#39;s icon. | [optional]
**thread_ts** | **string** | Parent message &#x60;ts&#x60; to post in a thread. | [optional]
**reply_broadcast** | **bool** | When true with thread_ts, broadcasts reply to channel. Default: false. | [optional]
**parse** | **string** | URL parsing: \&quot;full\&quot; (clickable links) or \&quot;none\&quot;. Default: \&quot;none\&quot;. | [optional]
**link_names** | **bool** | Convert channel and username refs to Slack links. Default: false. | [optional]
**mrkdwn** | **bool** | Enable Slack markup (*bold*, _italic_, &#x60;code&#x60;). Default: true. | [optional]
**unfurl_links** | **bool** | Unfurl link previews. Default: true. | [optional]
**unfurl_media** | **bool** | Unfurl media previews. Default: true. | [optional]
**metadata** | [**\Pingram\Model\GetTemplatesListResponseInnerAnyOf5Metadata**](GetTemplatesListResponseInnerAnyOf5Metadata.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
