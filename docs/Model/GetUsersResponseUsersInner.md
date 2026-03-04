# # GetUsersResponseUsersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique user identifier. Required. |
**email** | **string** | User&#39;s email address for email notifications. | [optional]
**number** | **string** | User&#39;s phone number for SMS/call notifications. | [optional]
**push_tokens** | [**\Pingram\Model\GetUsersResponseUsersInnerPushTokensInner[]**](GetUsersResponseUsersInnerPushTokensInner.md) | Mobile push tokens (FCM, APN) for push notifications. | [optional]
**web_push_tokens** | [**\Pingram\Model\GetUsersResponseUsersInnerWebPushTokensInner[]**](GetUsersResponseUsersInnerWebPushTokensInner.md) | Web push subscription config from the browser. | [optional]
**timezone** | **string** | User&#39;s timezone (e.g. \&quot;America/New_York\&quot;) for scheduling. | [optional]
**slack_channel** | **string** | The destination channel of slack notifications sent to this user. Can be either of the following: - Channel name, e.g. \&quot;test\&quot; - Channel name with # prefix, e.g. \&quot;#test\&quot; - Channel ID, e.g. \&quot;C1234567890\&quot; - User ID for DM, e.g. \&quot;U1234567890\&quot; - Username with @ prefix, e.g. \&quot;@test\&quot; | [optional]
**slack_token** | [**\Pingram\Model\GetUsersResponseUsersInnerSlackToken**](GetUsersResponseUsersInnerSlackToken.md) |  | [optional]
**last_seen_time** | **string** | Last activity timestamp. Updated automatically. Read-only. | [optional]
**updated_at** | **string** | Last update timestamp. Read-only. | [optional]
**created_at** | **string** | Creation timestamp. Read-only. | [optional]
**email_suppression_status** | [**\Pingram\Model\GetUsersResponseUsersInnerEmailSuppressionStatus**](GetUsersResponseUsersInnerEmailSuppressionStatus.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
