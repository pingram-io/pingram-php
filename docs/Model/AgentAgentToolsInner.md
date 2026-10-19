# # AgentAgentToolsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Transfer the live call to one of destinations. |
**destinations** | [**\Pingram\Model\TransferDestinationsInner[]**](TransferDestinationsInner.md) | Numbers the agent can transfer to. Set a condition on each when there is more than one. |
**name** | **string** | Function name the model calls. |
**description** | **string** | When the model should use this tool. |
**parameters** | **array<string,object>** | JSON Schema for the arguments the model passes. |
**url** | **string** | MCP server URL. |
**before_speech** | **string** | Spoken before the webhook when this turn has not spoken yet. | [optional]
**slow_speech_after_seconds** | **float** | Wait this many seconds, then speak slowSpeech if the webhook is still running. | [optional]
**slow_speech** | **string** | Spoken once when the webhook is still running after slowSpeechAfterSeconds. | [optional]
**label** | **string** | Optional name shown in the dashboard. | [optional]
**documents** | [**\Pingram\Model\KnowledgeDocumentsInner[]**](KnowledgeDocumentsInner.md) | Files the agent can search. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
