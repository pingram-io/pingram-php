# # WebhookEndpointUpsertRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**webhook** | **string** | Public HTTPS URL that accepts POST with a JSON event body. Return 2xx to acknowledge. Private, loopback, and link-local addresses are rejected. Requests include X-Pingram-Id, X-Pingram-Signature (v1 HMAC-SHA256), and X-Pingram-Timestamp. A username and password in this URL are stored separately and removed from the saved URL. |
**events** | **string[]** | Full set of event types to deliver to this URL. Omitting an event on update unsubscribes it. Inbound SMS to the free shared number only works when that person has already received a text from this number. Inbound SMS to a dedicated number works normally. |
**basic_auth** | [**\Pingram\Model\WebhookEndpointUpsertRequestBasicAuth**](WebhookEndpointUpsertRequestBasicAuth.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
