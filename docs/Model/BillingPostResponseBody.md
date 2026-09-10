# # BillingPostResponseBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **string** |  |
**account_type** | **string** |  |
**creator** | **string** |  | [optional]
**name** | **string** |  | [optional]
**messages_cap** | **float** |  |
**cost_cap** | **float** |  |
**sms_cap** | **float** |  | [optional]
**call_cap** | **float** |  | [optional]
**billing_version** | **float** | When omitted, defaults to LATEST_BILLING_VERSION. | [optional]
**anniversary_date** | **string** | ISO date (YYYY-MM-DD) when the billing cycle resets. |
**created_at** | **string** |  |
**updated_at** | **string** |  |
**status** | **string** |  | [optional]
**subscription_status** | **string** |  | [optional]
**pending_downgrade_effective_date** | **string** |  | [optional]
**pending_downgrade_cost_cap** | **float** |  | [optional]
**pending_downgrade_account_type** | **string** |  | [optional]
**auto_upgrade** | **bool** | When true, paid accounts move up one budget tier at 90% of the monthly budget. | [optional]
**session_id** | **string** |  | [optional]
**url** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
