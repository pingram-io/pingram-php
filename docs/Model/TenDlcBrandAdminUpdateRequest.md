# # TenDlcBrandAdminUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scenario_id** | **string** | Who the 10DLC brand is registered for. - own_brand: personal or company project - client_brand: agency or contractor | [optional]
**business_type** | **string** | Legal entity type for a 10DLC brand. - PRIVATE_PROFIT: private for-profit (LLC, corp, etc.) - SOLE_PROPRIETOR: sole proprietorship - PUBLIC_PROFIT: publicly traded for-profit - NON_PROFIT: non-profit - GOVERNMENT: government | [optional]
**legal_name** | **string** |  | [optional]
**display_name** | **string** | Brand display name (marketing/DBA); defaults to legalName when omitted on legalName-only updates. | [optional]
**first_name** | **string** |  | [optional]
**last_name** | **string** |  | [optional]
**tax_id** | **string** | For US companies (country US): 9-digit EIN (Employer Identification Number). For Canada (country CA): 9-digit BN (Business Number). For other countries: national business tax identifier. | [optional]
**website** | **string** |  | [optional]
**country** | **string** |  | [optional]
**street** | **string** |  | [optional]
**city** | **string** |  | [optional]
**state** | **string** |  | [optional]
**postal_code** | **string** |  | [optional]
**compliance_contact_email** | **string** |  | [optional]
**compliance_contact_phone** | **string** |  | [optional]
**vertical** | **string** | Industry vertical required before Pingram submits the brand to carriers. | [optional]
**entity_type** | **string** | Legacy only when businessType is Other. | [optional]
**brand_status** | **string** | Pingram-side brand registration workflow status. - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
