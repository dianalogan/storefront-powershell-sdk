#New-STFSamlEncryptionCertificate
Create a new encryption certificate to be used by the SAML Service Provider
##Syntax
```
```
##Detailed Description
Create a new encryption certificate to be used by SAML Service Provider, for the specified authentication service
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Authentication.AuthenticationService
Parameter AuthenticationService: A .NET class representing the configuration of a StoreFront Authentication service
###System.String
Parameter SubjectName: The .NET 'System.String' reference type
##Return Values
##Examples
###EXAMPLE 1 Create a new encryption certificate to be used by the SAML Service Provider.
```
New-STFSamlEncryptionCertificate -AuthenticationService $authentication -SubjectName Encryption
```
REMARKS

Create a new encryption certificate, with subject name 'Encryption', to be used by the SAML Service Provider in the
specified authentication service.
