#Get-STFPasswordManagerAccountSelfService
Gets the Password Manager account self-service method
##Syntax
```
```
##Detailed Description
Gets the Password Manager account self-service method (Password Reset).
##Related Commands
*[Set-STFPasswordManagerAccountSelfService](Set-STFPasswordManagerAccountSelfService)
*[Get-STFAccountSelfService](Get-STFAccountSelfService)
*[Set-STFAccountSelfService](Set-STFAccountSelfService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Authentication.AuthenticationService
Parameter AuthenticationService: A .NET class representing the configuration of a StoreFront Authentication service
##Return Values
###String
The .NET 'System.String' reference type
##Examples
###EXAMPLE 1 Get Password Manager settings
```
Get-STFAuthenticationServicePasswordManagerAccountSelfService -AuthenticationService $auth
```
REMARKS

Get the Password Manager settings for account self-service.
