# # TenDlcBrandUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scenario_id** | **string** |  | [optional]
**business_type** | **string** |  | [optional]
**legal_name** | **string** |  | [optional]
**display_name** | **string** | Brand display name (marketing/DBA); defaults to legalName when omitted on legalName-only updates. | [optional]
**first_name** | **string** |  | [optional]
**last_name** | **string** |  | [optional]
**vertical** | **string** |  | [optional]
**entity_type** | **string** | Admin-only; legacy Other records. Ignored on customer PATCH. | [optional]
**brand_status** | **string** | Pingram-side brand registration workflow status. - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome | [optional]
**tax_id** | **string** |  | [optional]
**website** | **string** |  | [optional]
**country** | **string** |  | [optional]
**street** | **string** |  | [optional]
**city** | **string** |  | [optional]
**state** | **string** |  | [optional]
**postal_code** | **string** |  | [optional]
**compliance_contact_email** | **string** |  | [optional]
**compliance_contact_phone** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
