# # VoiceBrowserCallRequestConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** |  |
**steps** | [**\Pingram\Model\ScriptStepsInner[]**](ScriptStepsInner.md) |  |
**voicemail_action** | **string** | What to do when an answering machine picks up. hangup ends the call, message plays voicemailMessage, continue keeps talking. Default: continue. | [optional]
**voicemail_message** | **string** |  | [optional]
**privacy** | [**\Pingram\Model\ScriptPrivacy**](ScriptPrivacy.md) |  | [optional]
**opener** | **string** |  | [optional]
**agent** | [**\Pingram\Model\AgentAgent**](AgentAgent.md) |  |
**greeting** | **string** |  | [optional]
**to** | **string** |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
