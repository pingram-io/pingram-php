# # TenDlcBrandCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scenario_id** | **string** | Who the 10DLC brand is registered for. - own_brand: personal or company project - client_brand: agency or contractor |
**business_type** | **string** | Legal entity type for a 10DLC brand. - PRIVATE_PROFIT: private for-profit (LLC, corp, etc.) - SOLE_PROPRIETOR: sole proprietorship - PUBLIC_PROFIT: publicly traded for-profit - NON_PROFIT: non-profit - GOVERNMENT: government |
**legal_name** | **string** |  |
**first_name** | **string** | Required when businessType is SOLE_PROPRIETOR. | [optional]
**last_name** | **string** | Required when businessType is SOLE_PROPRIETOR. | [optional]
**tax_id** | **string** | For US companies (country US): 9-digit EIN (Employer Identification Number). For Canada (country CA): 9-digit BN (Business Number). For other countries: national business tax identifier. Required except when businessType is SOLE_PROPRIETOR. | [optional]
**website** | **string** |  |
**country** | **string** |  |
**street** | **string** |  | [optional]
**city** | **string** |  | [optional]
**state** | **string** |  | [optional]
**postal_code** | **string** |  | [optional]
**compliance_contact_email** | **string** |  |
**compliance_contact_phone** | **string** |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
