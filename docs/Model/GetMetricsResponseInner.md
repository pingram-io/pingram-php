# # GetMetricsResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | &lt;p&gt;The short name you specified to represent this metric.&lt;/p&gt; | [optional]
**label** | **string** | &lt;p&gt;The human-readable label associated with the data.&lt;/p&gt; | [optional]
**timestamps** | **\DateTime[]** | &lt;p&gt;The timestamps for the data points, formatted in Unix timestamp format. The number of             timestamps always matches the number of values and the value for Timestamps[x] is             Values[x].&lt;/p&gt; | [optional]
**values** | **float[]** | &lt;p&gt;The data points for the metric corresponding to &lt;code&gt;Timestamps&lt;/code&gt;. The number of             values always matches the number of timestamps and the timestamp for Values[x] is             Timestamps[x].&lt;/p&gt; | [optional]
**status_code** | **string** |  | [optional]
**messages** | [**\Pingram\Model\GetMetricsResponseInnerMessagesInner[]**](GetMetricsResponseInnerMessagesInner.md) | &lt;p&gt;A list of messages with additional information about the data returned.&lt;/p&gt; | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
