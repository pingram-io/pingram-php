# # IngishtsPostRequestMetricDataQueriesInnerMetricStat

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**metric** | [**\Pingram\Model\IngishtsPostRequestMetricDataQueriesInnerMetricStatMetric**](IngishtsPostRequestMetricDataQueriesInnerMetricStatMetric.md) |  | [optional]
**period** | **float** | &lt;p&gt;The granularity, in seconds, of the returned data points. For metrics with regular             resolution, a period can be as short as one minute (60 seconds) and must be a multiple             of 60. For high-resolution metrics that are collected at intervals of less than one             minute, the period can be 1, 5, 10, 20, 30, 60, or any multiple of 60. High-resolution             metrics are those metrics stored by a &lt;code&gt;PutMetricData&lt;/code&gt; call that includes a             &lt;code&gt;StorageResolution&lt;/code&gt; of 1 second.&lt;/p&gt;          &lt;p&gt;If the &lt;code&gt;StartTime&lt;/code&gt; parameter specifies a time stamp that is greater than             3 hours ago, you must specify the period as follows or no data points in that time range             is returned:&lt;/p&gt;          &lt;ul&gt;             &lt;li&gt;                &lt;p&gt;Start time between 3 hours and 15 days ago - Use a multiple of 60 seconds                     (1 minute).&lt;/p&gt;             &lt;/li&gt;             &lt;li&gt;                &lt;p&gt;Start time between 15 and 63 days ago - Use a multiple of 300 seconds (5                     minutes).&lt;/p&gt;             &lt;/li&gt;             &lt;li&gt;                &lt;p&gt;Start time greater than 63 days ago - Use a multiple of 3600 seconds (1                     hour).&lt;/p&gt;             &lt;/li&gt;          &lt;/ul&gt; | [optional]
**stat** | **string** | &lt;p&gt;The statistic to return. It can include any CloudWatch statistic or extended             statistic.&lt;/p&gt; | [optional]
**unit** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
