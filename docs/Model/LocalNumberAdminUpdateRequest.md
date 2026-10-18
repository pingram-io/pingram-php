# # LocalNumberAdminUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome | [optional]
**registration_type** | **string** | Whether this local number is registered to a person or a business. - personal: an individual. firstName and lastName are that person. - business: a company. firstName and lastName are the authorized representative. | [optional]
**fields** | [**\Pingram\Model\LocalNumberAdminUpdateRequestFields**](LocalNumberAdminUpdateRequestFields.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
