# # TenDlcBrandUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scenario_id** | **string** | Who the 10DLC brand is registered for. - own_brand: personal or company project - client_brand: agency or contractor | [optional]
**business_type** | **string** | Legal entity type for a 10DLC brand. - PRIVATE_PROFIT: private for-profit (LLC, corp, etc.) - SOLE_PROPRIETOR: sole proprietorship - PUBLIC_PROFIT: publicly traded for-profit - NON_PROFIT: non-profit - GOVERNMENT: government | [optional]
**legal_name** | **string** | Official registered legal business name. For SOLE_PROPRIETOR, optional DBA or trade name (defaults to firstName and lastName). | [optional]
**display_name** | **string** | Public brand name shown to recipients and carriers. Use the name customers recognize (your DBA or trade name). For SOLE_PROPRIETOR, this is the brand you send as — not the individual&#39;s legal name. Omit to keep the existing value. If you change legalName and omit displayName, displayName is reset to the new legalName. | [optional]
**first_name** | **string** | Legal first name of the sole proprietor. Required when businessType is SOLE_PROPRIETOR. | [optional]
**last_name** | **string** | Legal last name of the sole proprietor. Required when businessType is SOLE_PROPRIETOR. | [optional]
**tax_id** | **string** | For US companies (country US): 9-digit EIN (Employer Identification Number). For Canada (country CA): 9-digit BN (Business Number). For other countries: national business tax identifier. Required except when businessType is SOLE_PROPRIETOR. | [optional]
**website** | **string** | Public website for the brand. Include a scheme (https://) or a domain; https:// is prepended when omitted. Carriers expect a working site with privacy policy and terms. | [optional]
**country** | **string** | ISO 3166-1 alpha-2 country of incorporation (for example US or CA). | [optional]
**street** | **string** | Street address that matches official tax registration. | [optional]
**city** | **string** | City that matches official tax registration. | [optional]
**state** | **string** | State (US) or province (CA) that matches official tax registration. | [optional]
**postal_code** | **string** | ZIP code (US) or postal code (CA) that matches official tax registration. | [optional]
**compliance_contact_email** | **string** | Email for the 10DLC compliance contact. Used for carrier and registration follow-up. | [optional]
**compliance_contact_phone** | **string** | Phone number for the 10DLC compliance contact. E.164 preferred; national numbers are normalized using country. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
