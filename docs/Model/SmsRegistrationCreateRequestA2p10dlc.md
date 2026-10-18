# # SmsRegistrationCreateRequestA2p10dlc

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**campaign_description** | **string** | Summary of what this campaign sends and why, including audience and typical message content. Required before carrier submission. | [optional]
**campaign_sample1** | **string** | Example SMS that represents actual campaign traffic. Required before carrier submission. Should match the use case and typically identify the brand and include STOP/HELP language. | [optional]
**campaign_sample2** | **string** | Second example SMS. Required before carrier submission. Required for MARKETING and MIXED use cases. | [optional]
**campaign_sample3** | **string** | Optional third example SMS. | [optional]
**campaign_sample4** | **string** | Optional fourth example SMS. | [optional]
**campaign_message_flow** | **string** | How recipients opt in (for example website form, checkout, or keyword). Describe the call-to-action and where consent is collected. Required before carrier submission. | [optional]
**campaign_optin_keywords** | **string** | Extra opt-in keywords as a comma-separated list. START is always included. | [optional]
**campaign_optin_message** | **string** | Auto-reply sent when a recipient opts in. Required before carrier submission. Should confirm the subscription, mention message frequency, and include STOP and HELP instructions. | [optional]
**campaign_optout_keywords** | **string** | Extra opt-out keywords as a comma-separated list. STOP is always included. | [optional]
**campaign_optout_message** | **string** | Auto-reply sent when a recipient opts out. Required before carrier submission. Should confirm they will receive no further messages. | [optional]
**campaign_help_keywords** | **string** | Extra help keywords as a comma-separated list. HELP is always included. | [optional]
**campaign_help_message** | **string** | Auto-reply sent when a recipient texts a help keyword. Required before carrier submission. Should include a support contact (email and/or phone). | [optional]
**campaign_embedded_link** | **bool** | Whether campaign messages include URLs. | [optional]
**campaign_embedded_link_url** | **string** | Sample URL that appears in messages. Provide when campaignEmbeddedLink is true. | [optional]
**campaign_embedded_phone** | **bool** | Whether campaign messages include phone numbers. | [optional]
**campaign_age_gated** | **bool** | Whether campaign content is age-restricted (18+). | [optional]
**campaign_direct_lending** | **bool** | Whether the campaign relates to direct lending or loan products. | [optional]
**campaign_privacy_policy_link** | **string** | Public URL of the privacy policy that covers this SMS program. | [optional]
**campaign_terms_and_conditions_link** | **string** | Public URL of the terms and conditions that cover this SMS program. | [optional]
**campaign_usecase** | **string** | 10DLC campaign use case submitted to carriers. Required before carrier submission. One of 2FA, ACCOUNT_NOTIFICATION, CUSTOMER_CARE, DELIVERY_NOTIFICATION, FRAUD_ALERT, MARKETING, MIXED, POLLING_VOTING, PUBLIC_SERVICE_ANNOUNCEMENT, or SECURITY_ALERT. For MIXED, append comma-separated sub-use cases after MIXED (sub-use cases cannot include MIXED), for example MIXED,2FA,ACCOUNT_NOTIFICATION. | [optional]
**scenario_id** | **string** | Who the 10DLC brand is registered for. - own_brand: personal or company project - client_brand: agency or contractor |
**business_type** | **string** | Legal entity type for a 10DLC brand. - PRIVATE_PROFIT: private for-profit (LLC, corp, etc.) - SOLE_PROPRIETOR: sole proprietorship - PUBLIC_PROFIT: publicly traded for-profit - NON_PROFIT: non-profit - GOVERNMENT: government |
**legal_name** | **string** | Official registered legal business name. For SOLE_PROPRIETOR, optional DBA or trade name (defaults to firstName and lastName). | [optional]
**display_name** | **string** | Public brand name shown to recipients and carriers. Use the name customers recognize (your DBA or trade name). For companies with no DBA, use the same value as legalName. For SOLE_PROPRIETOR, this is the brand you send as — not the individual&#39;s legal name (set firstName and lastName for that). If the sole proprietor has no DBA, use first and last name. |
**first_name** | **string** | Legal first name of the sole proprietor. Required when businessType is SOLE_PROPRIETOR. | [optional]
**last_name** | **string** | Legal last name of the sole proprietor. Required when businessType is SOLE_PROPRIETOR. | [optional]
**tax_id** | **string** | For US companies (country US): 9-digit EIN (Employer Identification Number). For Canada (country CA): 9-digit BN (Business Number). For other countries: national business tax identifier. Required except when businessType is SOLE_PROPRIETOR. | [optional]
**website** | **string** | Public website for the brand. Include a scheme (https://) or a domain; https:// is prepended when omitted. Carriers expect a working site with privacy policy and terms. |
**country** | **string** | ISO 3166-1 alpha-2 country of incorporation (for example US or CA). |
**street** | **string** | Street address that matches official tax registration. |
**city** | **string** | City that matches official tax registration. |
**state** | **string** | State (US) or province (CA) that matches official tax registration. |
**postal_code** | **string** | ZIP code (US) or postal code (CA) that matches official tax registration. |
**compliance_contact_email** | **string** | Email for the 10DLC compliance contact. Used for carrier and registration follow-up. |
**compliance_contact_phone** | **string** | Phone number for the 10DLC compliance contact. E.164 preferred; national numbers are normalized using country. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
