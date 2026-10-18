# # SmsRegistrationSenderId

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | **string** | ISO 3166-1 alpha-2 destination country. |
**sender_id** | **string** | The account Sender ID, or null when none has been submitted. |
**availability** | **string** | Whether the account Sender ID can be used for a destination country. - available: the Sender ID can be enabled for this country - unsupported: sending to this country with a Sender ID is not supported - contact_us: not available yet; contact us about support for this country |
**registration_required** | **bool** | True when this country requires Sender ID registration before it can be enabled. |
**added** | **bool** | True when this country has been added for the account Sender ID. |
**enabled** | **bool** | True when the account Sender ID can be used to send to this country. |
**message** | **string** | What is needed next, or why the Sender ID cannot be used for this country. |
**status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
