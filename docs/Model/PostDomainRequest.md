# # PostDomainRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domain** | **string** | Domain you own. A subdomain such as mail.example.com is recommended. Mail from a subdomain is easier to deliver, and receiving mail there does not replace mail already arriving at the bare domain. |
**inbound** | **bool** | Receive mail for this domain. Leave this out to send only. | [optional]
**open_tracking** | **bool** | Record when someone opens mail from this domain. False turns opens off. You can record opens without recording clicks. | [optional]
**click_tracking** | **bool** | Record when someone clicks a link in mail from this domain. False turns clicks off. You can record clicks without recording opens. | [optional]
**tracking_subdomain** | **string** | Host label for this domain, such as links or go. The domain name is added after it. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
