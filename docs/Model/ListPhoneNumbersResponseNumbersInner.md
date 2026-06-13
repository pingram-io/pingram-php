# # ListPhoneNumbersResponseNumbersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **string** | E.164 |
**label** | **string** |  | [optional]
**created_at** | **string** | ISO timestamp when the number was registered |
**country_code** | **string** | ISO 3166-1 alpha-2 country code |
**number_type** | **string** | e.g. local, toll_free |
**billing_status** | **string** | active or released |
**next_billing_date** | **string** | YYYY-MM-DD next monthly rent charge |
**monthly_price** | **float** | Monthly cost in USD |
**a2p_status** | **string** | US 10DLC readiness derived from stored campaign assignment | [optional]
**released_at** | **string** | ISO timestamp when the number was released (released numbers only) | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
