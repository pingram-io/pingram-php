# # OrganizationUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_usage** | **float** | Total message usage (EMAIL + INAPP_WEB + WEB_PUSH + PUSH + SLACK) |
**budget_usage** | **float** | Total budget usage in USD (cost_SMS + cost_CALL) |
**cost_sms** | **float** | SMS cost in USD |
**cost_call** | **float** | Call cost in USD |
**channel_usages** | **array<string,float>** | Per-channel usage breakdown |
**billing_cycle_start** | **string** | Billing cycle start date (ISO string) |
**billing_cycle_end** | **string** | Billing cycle end date (ISO string) |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
