# # GetSendersResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domain** | **string** | Domain name, such as mail.example.com. |
**status** | **string** | Whether sending from this domain is not started, waiting, verified, temporarily failing, or failed. Mail goes out when this is &#x60;SUCCESS&#x60; or &#x60;TEMPORARY_FAILURE&#x60;. |
**inbound** | **bool** | Whether this domain is set to receive mail. This is your choice, not the MX record. |
**open_tracking** | **bool** | Whether new mail from this domain records opens. This is your choice, not the tracking host. |
**click_tracking** | **bool** | Whether new mail from this domain records link clicks. This is your choice, not the tracking host. |
**tracking_subdomain** | **string** | Host label for tracked links, such as links. Absent until tracking has a host. | [optional]
**dns_records** | [**\Pingram\Model\GetSendersResponseInnerDnsRecordsInner[]**](GetSendersResponseInnerDnsRecordsInner.md) | DNS records to publish for this domain. Every record we can show is listed. &#x60;expected&#x60; is false when the current settings do not need it. &#x60;status&#x60; is the row to show. |
**detail** | **string** | Plain summary of sending, receiving, and tracking. Names each record and whether it is verified, waiting, missing, or turned off. |
**created_at** | **string** | When this domain was added. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
