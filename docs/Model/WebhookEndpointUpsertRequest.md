# # WebhookEndpointUpsertRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**webhook** | **string** | Public http or https URL that accepts POST with a JSON event body. Return 2xx to acknowledge. Requests include X-Pingram-Id, X-Pingram-Signature (v1 HMAC-SHA256), and X-Pingram-Timestamp. |
**events** | **string[]** | Full set of event types to deliver to this URL. Omitting an event on update unsubscribes it. Inbound SMS to the free shared number only works when that person has already received a text from this number. Inbound SMS to a dedicated number works normally. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
