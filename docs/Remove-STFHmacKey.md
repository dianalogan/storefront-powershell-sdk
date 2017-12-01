#Remove-STFHmacKey
Remove a named HMAC key stored from a web service.
##Syntax
```
```
##Detailed Description
Remove an existing named HMAC key stored from a web service.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.StoreFrontWebService
Parameter WebService: The .NET 'Citrix.StoreFront.Model.StoreFrontWebService' reference type
###System.String
Parameter Name: The .NET 'System.String' reference type
##Return Values
##Examples
###EXAMPLE 1 Remove an existing HMAC key named 'test' from the specified Store service.
```
Remove-STFHmacKey -WebService $store -Name 'test'
```
REMARKS

Remove the existing HMAC key named 'test' from the specified Store service.
