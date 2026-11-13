# # TransferDestinationsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **string** | E.164 number to transfer the caller to. |
**condition** | **string** | When the model should choose this number. Required when more than one destination is set. |
**hold_say** | **string** | Spoken once to the caller while they wait. If holdAudio is also set, this sentence plays first and then the audio. | [optional]
**hold_audio** | **string** | &#x60;builtin:soft-piano&#x60;, &#x60;builtin:calm&#x60;, &#x60;builtin:bright&#x60;, or an HTTPS MP3 or WAV. Loops until the call connects. Omit it and the caller hears ringing. | [optional]
**receiver_instruction** | **string** | Shown to the agent with this number. Tells it whether and how to write the sentence spoken to the person who answers. Never spoken. Omit it and the agent is asked to say who is calling and why. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
