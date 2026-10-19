# # Custom

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Invoke an HTTPS webhook when the model calls this tool. |
**name** | **string** | Function name the model calls. |
**description** | **string** | When the model should use this tool. |
**parameters** | **array<string,mixed>** | JSON Schema for the arguments the model passes. |
**url** | **string** | HTTPS webhook invoked when the model calls this tool during a call. | [optional]
**before_speech** | **string** | Spoken before the webhook when this turn has not spoken yet. | [optional]
**slow_speech_after_seconds** | **float** | Wait this many seconds, then speak slowSpeech if the webhook is still running. | [optional]
**slow_speech** | **string** | Spoken once when the webhook is still running after slowSpeechAfterSeconds. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
