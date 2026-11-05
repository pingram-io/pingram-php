# # StartChangeEmailRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**new_email** | **string** |  |
**password** | **string** | Current account password. Required when the account already has a password. | [optional]
**new_password** | **string** | Password to set. Required when the account has no password yet, so the new email address can be used to sign in after social sign-in is removed. | [optional]
**mfa_code** | **string** | TOTP code. Required when software-token MFA is enabled on an account that has a password. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
