#Get-STFHmacKey
Get a named HMAC key from a web service.
##Syntax
```
```
##Detailed Description
Get a named HMAC key from a web service.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.StoreFrontWebService
Parameter WebService: The .NET 'Citrix.StoreFront.Model.StoreFrontWebService' reference type
###System.String
Parameter Name: The .NET 'System.String' reference type
##Return Values
###String
The .NET 'System.String' reference type
##Examples
###EXAMPLE 1 Get the HMAC key named 'logoffTicket' from the specified Store service.
```
Get-STFHmacKey -WebService $store -Name 'logoffTicket'
```
REMARKS

Get the HMAC key named 'logoffTicket' from the specified Store service.
OUTPUT
```
```