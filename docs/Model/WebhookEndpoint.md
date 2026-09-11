# # WebhookEndpoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this endpoint within the account. |
**webhook** | **string** | Destination URL that receives webhook event payloads. |
**events** | **string[]** | List of subscribed event types for this endpoint. |
**secret** | **string** | HMAC secret for verifying webhook signatures. Use this with your X-Pingram-Signature verification. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
