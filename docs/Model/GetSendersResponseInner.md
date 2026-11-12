# # GetSendersResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**waiting_for** | **string** | What is still missing before new mail can use the tracking subdomain. | [optional]
**sender** | **string** |  |
**status** | **string** |  |
**last_sync** | **\DateTime** |  |
**verification_tokens** | **string[]** |  | [optional]
**mail_from_domain_status** | **string** |  | [optional]
**created_at** | **string** |  |
**private_dkim_key** | **string** |  | [optional]
**reminder_sent_at** | **string** |  | [optional]
**selector** | **string** |  |
**verification_records** | [**\Pingram\Model\GetSendersResponseInnerVerificationRecords**](GetSendersResponseInnerVerificationRecords.md) |  | [optional]
**tracking_subdomain** | **string** | Subdomain recipients see on click tracking, the open pixel, and the unsubscribe page, such as links. | [optional]
**tracking_status** | **string** | Whether tracked links on this subdomain are not started, waiting, active, or failed. | [optional]
**tracking_failure_reason** | **string** | Why tracked links on this subdomain are not active, when setup did not succeed. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
