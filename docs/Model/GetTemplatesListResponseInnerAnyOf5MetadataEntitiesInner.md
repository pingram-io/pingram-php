# # GetTemplatesListResponseInnerAnyOf5MetadataEntitiesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**entity_type** | **string** | Entity type (e.g., &#39;slack#/entities/task&#39;, &#39;slack#/entities/file&#39;). |
**entity_payload** | **array<string,mixed>** | Schema for the given entity type. |
**external_ref** | [**\Pingram\Model\GetTemplatesListResponseInnerAnyOf5MetadataEntitiesInnerExternalRef**](GetTemplatesListResponseInnerAnyOf5MetadataEntitiesInnerExternalRef.md) |  |
**url** | **string** | URL used to identify an entity within the developer&#39;s system. |
**app_unfurl_url** | **string** | The exact URL posted in the source message. Required in metadata passed to &#x60;chat.unfurl&#x60;. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
