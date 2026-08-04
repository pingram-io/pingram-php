# # ListInvoicesResponseInvoicesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  |
**number** | **string** | Human-readable invoice number, when assigned. | [optional]
**status** | **string** |  | [optional]
**currency** | **string** |  |
**total** | **float** | Total amount due on the invoice (cents). |
**amount_due** | **float** |  |
**amount_paid** | **float** |  |
**created** | **float** | Unix timestamp (seconds) when the invoice was created. |
**hosted_invoice_url** | **string** | Stripe-hosted invoice page (receipt / pay). | [optional]
**invoice_pdf** | **string** | Direct PDF download URL. | [optional]
**period_start** | **float** | Billing period start (unix seconds), when applicable. | [optional]
**period_end** | **float** | Billing period end (unix seconds), when applicable. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
