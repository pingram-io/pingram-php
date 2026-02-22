# # SenderPostBodyUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  |
**email** | **string** |  | [optional]
**number** | **string** |  | [optional]
**push_tokens** | [**\Pingram\Model\GetUsersResponseUsersInnerPushTokensInner[]**](GetUsersResponseUsersInnerPushTokensInner.md) |  | [optional]
**web_push_tokens** | [**\Pingram\Model\GetUsersResponseUsersInnerWebPushTokensInner[]**](GetUsersResponseUsersInnerWebPushTokensInner.md) |  | [optional]
**timezone** | **string** |  | [optional]
**slack_channel** | **string** | The destination channel of slack notifications sent to this user. Can be either of the following: - Channel name, e.g. \&quot;test\&quot; - Channel name with # prefix, e.g. \&quot;#test\&quot; - Channel ID, e.g. \&quot;C1234567890\&quot; - User ID for DM, e.g. \&quot;U1234567890\&quot; - Username with @ prefix, e.g. \&quot;@test\&quot; | [optional]
**slack_token** | [**\Pingram\Model\GetUsersResponseUsersInnerSlackToken**](GetUsersResponseUsersInnerSlackToken.md) |  | [optional]
**last_seen_time** | **string** |  | [optional]
**updated_at** | **string** |  | [optional]
**created_at** | **string** |  | [optional]
**email_suppression_status** | [**\Pingram\Model\GetUsersResponseUsersInnerEmailSuppressionStatus**](GetUsersResponseUsersInnerEmailSuppressionStatus.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
