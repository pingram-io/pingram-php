# # StartPasswordChangeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**password** | **string** | New password. |
**current_password** | **string** | Current password. Required when the account already has one. | [optional]
**mfa_code** | **string** | TOTP code. Required when software-token MFA is enabled and the account has a password. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
