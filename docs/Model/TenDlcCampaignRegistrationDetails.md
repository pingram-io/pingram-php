# # TenDlcCampaignRegistrationDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **string** |  |
**campaign_status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome |
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
**created_at** | **string** |  |
**updated_at** | **string** |  |
**campaign_id** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
