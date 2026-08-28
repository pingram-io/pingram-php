# # TenDlcBrandRegistrationDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **string** |  |
**scenario_id** | **string** |  |
**business_type** | **string** |  |
**legal_name** | **string** |  |
**display_name** | **string** | Brand display name (marketing/DBA); defaults to legalName on customer submit. | [optional]
**first_name** | **string** |  | [optional]
**last_name** | **string** |  | [optional]
**tax_id** | **string** |  | [optional]
**website** | **string** |  |
**country** | **string** |  |
**street** | **string** |  | [optional]
**city** | **string** |  | [optional]
**state** | **string** |  | [optional]
**postal_code** | **string** |  | [optional]
**full_address** | **string** | Legacy records only; new submissions use structured address fields. | [optional]
**compliance_contact_email** | **string** |  |
**compliance_contact_phone** | **string** |  |
**brand_status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome |
**campaign_status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome |
**created_at** | **string** |  |
**updated_at** | **string** |  |
**vertical** | **string** | Industry vertical required before Pingram submits the brand to carriers (for example TECHNOLOGY, HEALTHCARE, RETAIL, or FINANCIAL). | [optional]
**entity_type** | **string** | Legacy only when businessType is Other. | [optional]
**profile_id** | **string** |  | [optional]
**brand_id** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
