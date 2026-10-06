# # AccountGetResponseBillingAlerts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** | When false, saved addresses and thresholds are kept but no email is sent. |
**emails** | **string[]** | Addresses that receive threshold emails. At most three. |
**thresholds** | **float[]** | Percents to email, from 5 to 100 in steps of 5. At most two. At least one is required while enabled. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
