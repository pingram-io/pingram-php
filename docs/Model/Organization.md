# # Organization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization_id** | **string** |  |
**organization_type** | **string** |  |
**creator** | **string** |  |
**messages_cap** | **float** |  |
**cost_cap** | **float** |  |
**created_at** | **string** |  |
**updated_at** | **string** |  |
**anniversary_date** | **string** | ISO date (YYYY-MM-DD) when the billing cycle resets. |
**allow_overage** | **bool** |  |
**name** | **string** |  |
**sms_cap** | **float** |  | [optional]
**call_cap** | **float** |  | [optional]
**stripe_customer_id** | **string** | Stripe subscription ID. | [optional]
**stripe_subscription_id** | **string** |  | [optional]
**subscription_status** | **string** |  | [optional]
**status** | **string** | Verification status; internalCap applies when not &#39;verified&#39;. | [optional]
**internal_cap** | **float** | Unverified account cap (per-channel message limit). | [optional]
**pending_downgrade_cost_cap** | **float** |  | [optional]
**pending_downgrade_messages_cap** | **float** |  | [optional]
**pending_downgrade_sms_cap** | **float** |  | [optional]
**pending_downgrade_call_cap** | **float** |  | [optional]
**pending_downgrade_internal_cap** | **float** |  | [optional]
**pending_downgrade_effective_date** | **string** |  | [optional]
**pending_downgrade_account_type** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
