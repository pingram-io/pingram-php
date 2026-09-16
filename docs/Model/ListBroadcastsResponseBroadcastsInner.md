# # ListBroadcastsResponseBroadcastsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**broadcast_id** | **string** | UUIDv7 (time-ordered). |
**name** | **string** |  |
**status** | **string** | Lifecycle status of an email broadcast. |
**paused_reason** | **string** |  | [optional]
**type** | **string** | Notification type id. Required before send or schedule. | [optional]
**channel** | **string** | Email-only in v1; forward-compatible field. |
**audience** | [**\Pingram\Model\BroadcastResponseAudience**](BroadcastResponseAudience.md) |  |
**from_name** | **string** |  |
**from_address** | **string** |  |
**reply_to_address** | **string** |  | [optional]
**subject** | **string** |  |
**schedule_at** | **string** | ISO datetime for scheduled broadcasts. | [optional]
**archived_at** | **string** | Set when the user archives the broadcast; hidden from the default list. | [optional]
**created_at** | **string** |  |
**updated_at** | **string** |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
