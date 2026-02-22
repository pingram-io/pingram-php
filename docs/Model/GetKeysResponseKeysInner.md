# # GetKeysResponseKeysInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for the key (jti) |
**key** | **string** | The full key string with prefix (shown for reference but should be stored securely by user) |
**key_type** | **string** | Type of API key |
**environment_id** | **string** | Environment ID if the key is scoped to a specific environment | [optional]
**account_id** | **string** | The account ID that owns this key |
**name** | **string** | Human-readable name/description for the key |
**revoked** | **bool** | Whether the key has been revoked |
**created_at** | **string** | ISO 8601 timestamp when the key was created |
**last_used_at** | **string** | ISO 8601 timestamp of when the key was last used (if tracked) | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
