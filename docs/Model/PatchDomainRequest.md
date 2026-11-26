# # PatchDomainRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inbound** | **bool** | Receive mail for this domain. Leave this out to keep the current choice. | [optional]
**open_tracking** | **bool** | Record when someone opens mail from this domain. Leave this out to keep the current choice. You can record opens without recording clicks. | [optional]
**click_tracking** | **bool** | Record when someone clicks a link in mail from this domain. Leave this out to keep the current choice. You can record clicks without recording opens. | [optional]
**tracking_subdomain** | **string** | Host label for this domain, such as links or go. The domain name is added after it. Leave this out to keep the current host. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
