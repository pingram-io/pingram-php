# # LogsDeliveryStatusResponseStatusesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tracking_id** | **string** | Opaque id returned when the notification was accepted. |
**channel** | **string** | Channel named on a delivery-status row. Email and SMS only. Coarse labels: no address or provider id. | [optional]
**status** | **string** | Delivery outcome for one request or one channel. These are the same states shown in the dashboard status column. |
**updated_at** | **string** | ISO 8601 time this outcome was recorded. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
