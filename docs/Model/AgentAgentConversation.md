# # AgentAgentConversation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**turn_detection** | **string** | How the agent decides the caller has finished speaking. Default: semantic. | [optional]
**min_end_of_turn_silence_ms** | **float** | Silence before the agent treats the turn as finished, in milliseconds. Default: 500. | [optional]
**allow_interruptions** | **bool** | Whether the caller can interrupt the agent. Default: true. | [optional]
**min_interruption_duration_ms** | **float** | How long the caller must speak to count as an interruption, in milliseconds. Default: 300. | [optional]
**silence_timeout_seconds** | **float** | Seconds of silence before the agent hangs up. 0 never hangs up. Default: 30. | [optional]
**max_call_length_seconds** | **float** | Maximum call length in seconds. Default: 600. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
