#Add-STFHmacKey
Add a named HMAC key stored to a web service.
##Syntax
```
```
##Detailed Description
Add a new named HMAC key stored to a web service.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.StoreFrontWebService
Parameter WebService: The .NET 'Citrix.StoreFront.Model.StoreFrontWebService' reference type
###System.String
Parameter Name: The .NET 'System.String' reference type
###System.String
Parameter Key: The .NET 'System.String' reference type
##Return Values
##Examples
###EXAMPLE 1 Add a new HMAC key named 'test' into the specified Store service, with the specified key.
```
Add-STFHmacKey -WebService $store -Name 'test' -Key '6UA064hC8Dx/5/s0irY3Vc+tYUh2d6TqPMjC4Qy1NTtCwusyA39mXJTXXPuLaLI7x2wDhFDrsk0rqSqzjlV5Pw=='
```
REMARKS

Add the new HMAC key named 'test' into the specified Store service, with the specified key.

```
Add-STFHmacKey -WebService $store -Name 'test'
```
REMARKS

Add the new HMAC key named 'test' into the specified Store service, with a randomly generated key.
