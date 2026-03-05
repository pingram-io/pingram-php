# # TemplatePatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**html** | **string** | HTML body of the email. | [optional]
**preview_text** | **string** | Preview text (e.g. for inbox). | [optional]
**internal** | **string** | Internal editor representation of the email content (e.g. Bee or Redactor JSON). Used for editing and component embedding; the actual email sent to recipients uses the html field. | [optional]
**subject** | **string** | Email subject line. | [optional]
**sender_name** | **string** | Sender display name. | [optional]
**sender_email** | **string** | Sender email address. | [optional]
**title** | **string** | Notification title (in-app). | [optional]
**redirect_url** | **string** | URL to open when the user taps the notification. | [optional]
**image_url** | **string** | Image URL shown in the in-app notification. | [optional]
**instant** | [**\Pingram\Model\TemplatePatchRequestInstant**](TemplatePatchRequestInstant.md) |  | [optional]
**batch** | [**\Pingram\Model\TemplatePatchRequestBatch**](TemplatePatchRequestBatch.md) |  | [optional]
**text** | **string** | Message text (SMS or call). | [optional]
**message** | **string** | Push notification body text. (title is shared with INAPP_WEB above.) | [optional]
**icon** | **string** | Web push: icon URL. Slack: bot icon (emoji or URL). | [optional]
**url** | **string** | Web push: URL to open when the notification is clicked. | [optional]
**blocks** | **array<string,mixed>[]** | Slack message blocks (optional). | [optional]
**username** | **string** | Slack bot username. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
