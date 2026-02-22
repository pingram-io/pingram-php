# # BillingPostResponseBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **string** |  |
**name** | **string** |  | [optional]
**account_type** | **string** |  |
**created_at** | **string** |  |
**creator** | **string** |  | [optional]
**stripe_customer_id** | **string** |  | [optional]
**stripe_subscription_id** | **string** |  | [optional]
**subscription_status** | **string** |  | [optional]
**anniversary_date** | **string** | ISO date (YYYY-MM-DD) when the billing cycle resets. Used for anniversary-based billing. | [optional]
**pending_downgrade_effective_date** | **string** | ISO date (YYYY-MM-DD) when the pending downgrade takes effect | [optional]
**pending_downgrade_account_type** | **string** | The account type to switch to when downgrade takes effect | [optional]
**pending_downgrade_usage_limit** | [**\Pingram\Model\BillingPostResponseBodyPendingDowngradeUsageLimit**](BillingPostResponseBodyPendingDowngradeUsageLimit.md) |  | [optional]
**session_id** | **string** |  | [optional]
**url** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
