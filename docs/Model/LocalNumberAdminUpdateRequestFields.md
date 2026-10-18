# # LocalNumberAdminUpdateRequestFields

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **string** | First name. For a business registration, the authorized representative. |
**last_name** | **string** | Last name. For a business registration, the authorized representative. |
**contact_phone** | **string** | Contact phone number. |
**street** | **string** | Street address, including the building number and street name. An IL registration also includes the apartment or suite. |
**city** | **string** | City. |
**postal_code** | **string** | Postal or ZIP code. |
**building_number** | **string** | Building number when it is sent separately from the street address. | [optional]
**state** | **string** | State or province. Required for an IL registration. | [optional]
**company_name** | **string** | Company name. Required for a business registration. | [optional]
**company_website** | **string** | Company website, including https://. Required for a GB business registration. | [optional]
**business_use_case** | **string** | How this number will be used. Required. A personal registration describes the inbound line, such as appointment reminders or two-factor authentication codes. A business registration describes messages sent to people who opted in, such as appointment reminders or delivery updates. | [optional]
**sub_allocated** | **bool** | True when someone else, such as a client, will use the number. False when you or your business will use it. | [optional]
**sub_allocated_party** | **string** | Name of the person or business who will use the number. Required when subAllocated is true. | [optional]
**address_country** | **string** | Country of the address, as a country name or an ISO 3166-1 alpha-2 code. Required for an IL registration, which can use an address outside Israel. A GB registration uses a United Kingdom address and does not send this field. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
