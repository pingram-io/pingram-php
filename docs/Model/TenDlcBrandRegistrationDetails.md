# # TenDlcBrandRegistrationDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **string** |  |
**scenario_id** | **string** |  |
**business_type** | **string** |  |
**legal_name** | **string** | Official registered legal business name. For SOLE_PROPRIETOR, may be a DBA or trade name. |
**display_name** | **string** | Public brand name shown to recipients and carriers. | [optional]
**first_name** | **string** | Legal first name of the sole proprietor. Present when businessType is SOLE_PROPRIETOR. | [optional]
**last_name** | **string** | Legal last name of the sole proprietor. Present when businessType is SOLE_PROPRIETOR. | [optional]
**tax_id** | **string** | For US companies (country US): 9-digit EIN (Employer Identification Number). For Canada (country CA): 9-digit BN (Business Number). For other countries: national business tax identifier. Omitted when businessType is SOLE_PROPRIETOR. | [optional]
**website** | **string** | Public website for the brand. |
**country** | **string** | ISO 3166-1 alpha-2 country of incorporation (for example US or CA). |
**street** | **string** | Street address that matches official tax registration. | [optional]
**city** | **string** | City that matches official tax registration. | [optional]
**state** | **string** | State (US) or province (CA) that matches official tax registration. | [optional]
**postal_code** | **string** | ZIP code (US) or postal code (CA) that matches official tax registration. | [optional]
**full_address** | **string** | Legacy records only; new submissions use structured address fields. | [optional]
**compliance_contact_email** | **string** | Email for the 10DLC compliance contact. |
**compliance_contact_phone** | **string** | Phone number for the 10DLC compliance contact. |
**brand_status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome |
**campaign_status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome |
**created_at** | **string** |  |
**updated_at** | **string** |  |
**vertical** | **string** | Industry vertical required before Pingram submits the brand to carriers (for example TECHNOLOGY, HEALTHCARE, RETAIL, or FINANCIAL). | [optional]
**entity_type** | **string** | Legacy only when businessType is Other. | [optional]
**profile_id** | **string** |  | [optional]
**brand_id** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
