# # CreateKeyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for the key (jti) |
**key** | **string** | The full API key string - ONLY returned on creation, never shown again |
**key_type** | **string** | Type of API key that was created |
**environment_id** | **string** | Environment ID if the key is scoped to a specific environment | [optional]
**name** | **string** | Human-readable name/description for the key |
**created_at** | **string** | ISO 8601 timestamp when the key was created |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
