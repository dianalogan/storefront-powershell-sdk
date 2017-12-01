#Export-STFSamlEncryptionCertificate
Export the encryption certificate to be used by SAML Identity Providers
##Syntax
```
```
##Detailed Description
Export, from the specified authentication service, the encryption certificate to be used by SAML Identity Providers
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Authentication.AuthenticationService
Parameter AuthenticationService: A .NET class representing the configuration of a StoreFront Authentication service
###System.String
Parameter FilePath: The .NET 'System.String' reference type
##Return Values
##Examples
###EXAMPLE 1 Export the encryption certificate to be used by the SAML IdentityProvider.
```
Export-STFSamlEncryptionCertificate -AuthenticationService $authentication -FilePath C:\windows\temp\EncryptionCertificate.cer
```
REMARKS

Export the encryption certificate to be used by the SAML Identity Provider.
