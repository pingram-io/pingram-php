# # GetGroupTextLogResponseLogsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tracking_id** | **string** | Tracking id of this group text. |
**direction** | **string** | Whether this row is a send or a message someone typed. |
**from** | **string** | Sending number, or the number that typed an inbound message. |
**participants** | **string[]** | The other numbers, in the order they were sent. |
**text** | **string** | Text that was sent or received. | [optional]
**subject** | **string** | Subject shown with an outbound group text. | [optional]
**media** | **string[]** | Pictures or files attached to this group text. | [optional]
**cost** | **float** | Sum of the per-recipient multimedia message price. | [optional]
**type** | **string** | Notification type from the send. | [optional]
**sent_at** | **string** | When the send was accepted. | [optional]
**delivered_at** | **string** | When the first number was delivered. | [optional]
**failed_at** | **string** | When the send was rejected. | [optional]
**failure_code** | **string** | Why the send was rejected. | [optional]
**failure_internal** | **string** | Extra detail for support. Omitted for other callers. | [optional]
**recipient_delivered_at** | **array<string,string>** | When each number was delivered. | [optional]
**recipient_failed_at** | **array<string,string>** | When each number failed. | [optional]
**recipient_failure_code** | **array<string,string>** | Why each number failed. | [optional]
**our_number** | **string** | Number on your account that is in an inbound group text. | [optional]
**received_at** | **string** | When an inbound message arrived. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
