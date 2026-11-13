# # TransferCallRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**to** | **string** | E.164 number to move the caller to. |
**hold_say** | **string** | Spoken once to the caller while they wait. If holdAudio is also set, this sentence plays first and then the audio. | [optional]
**hold_audio** | **string** | &#x60;builtin:soft-piano&#x60;, &#x60;builtin:calm&#x60;, &#x60;builtin:bright&#x60;, or an HTTPS MP3 or WAV. Loops until the call connects. Omit it and the caller hears ringing. | [optional]
**receiver_say** | **string** | Spoken to the person who answers, before the caller is connected. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
