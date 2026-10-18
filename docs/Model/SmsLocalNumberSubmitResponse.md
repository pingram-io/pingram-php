# # SmsLocalNumberSubmitResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mock** | **bool** |  |
**submitted** | **bool** |  |
**country** | **string** | GB and IL local-number registration. |
**status** | **string** | Pingram-side 10DLC registration workflow status (brand or campaign). - not_started: no customer submission yet - pending_review: customer submitted; Pingram has not submitted to carriers - in_progress: submitted for carrier review - approved | rejected | info_needed: review outcome |
**requirement_group_id** | **string** |  | [optional]
**requirement_status** | **string** |  | [optional]
**slots** | [**\Pingram\Model\SmsLocalNumberSubmitResponseSlotsInner[]**](SmsLocalNumberSubmitResponseSlotsInner.md) |  |
**questions** | [**\Pingram\Model\SmsLocalNumberSubmitResponseQuestionsInner[]**](SmsLocalNumberSubmitResponseQuestionsInner.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
