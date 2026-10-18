# # SmsRegistrationCreateRequestLocalNumberDocumentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**doc_kind** | **string** | Which document this is. - passport_or_id: GB personal, with utility_bill. - utility_bill: needed for GB registration; must be less than 3 months old. - company_registration_certificate: GB business, with utility_bill. - proof_of_address: needed for IL registration; must be less than 3 months old. - business_registration_certificate: IL business, with proof_of_address. |
**file_name** | **string** | File name, including an image or PDF extension. |
**content** | **string** | Base64-encoded image or PDF. | [optional]
**url** | **string** | HTTPS URL of an image or PDF, up to 10 MB. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
