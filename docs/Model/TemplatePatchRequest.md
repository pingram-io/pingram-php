# # TemplatePatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**html** | **string** | HTML body of the email. | [optional]
**internal** | **string** | Internal editor representation of the email content (e.g. Bee or Redactor JSON). Used for editing and component embedding; the actual email sent to recipients uses the html field. | [optional]
**subject** | **string** | Email subject line. | [optional]
**sender_name** | **string** | Sender display name. | [optional]
**sender_email** | **string** | Sender email address. | [optional]
**migration** | **string** | Migration metadata (e.g. from template migration). | [optional]
**title** | **string** | Notification title (in-app). | [optional]
**redirect_url** | **string** | URL to open when the user taps the notification. | [optional]
**image_url** | **string** | Image URL shown in the in-app notification. | [optional]
**instant** | [**\Pingram\Model\TemplatePatchRequestAnyOf1Instant**](TemplatePatchRequestAnyOf1Instant.md) |  | [optional]
**batch** | [**\Pingram\Model\TemplatePatchRequestAnyOf1Batch**](TemplatePatchRequestAnyOf1Batch.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
