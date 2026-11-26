# # GetSendersResponseInnerDnsRecordsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  |
**type** | **string** | TXT, MX, or CNAME. |
**name** | **string** | Name to enter at the DNS host. &#x60;@&#x60; is the bare domain. |
**host** | **string** | Full hostname, such as pingram._domainkey.mail.example.com. |
**value** | **string** | Exact value to publish. |
**priority** | **float** | MX priority. Present for the bounce and inbound records. | [optional]
**expected** | **bool** | Whether the current settings expect this record. Inbound is expected when receiving is on. Tracking is expected when open or click tracking is on. The record is still listed when this is false. |
**status** | **string** | Whether this record is ready to use. &#x60;PENDING&#x60; means it has been seen and confirmation is not finished. &#x60;TEMPORARY_FAILURE&#x60; means a confirmed record has started to disappear. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
