#Get-STFStoreService
Gets the StoreFront Store Services matching the supplied parameter criteria.
##Syntax
```
Get-STFStoreService [-AuthenticationService] <AuthenticationService> [[-VirtualPath] <String>] [[-SiteId] <Int64>] [<CommonParameters>]
Get-STFStoreService [-WebReceiverService] <WebReceiverService> [[-VirtualPath] <String>] [[-SiteId] <Int64>] [<CommonParameters>]
```
##Detailed Description
StoreFront Store Services are deployed to specific IIS virtual paths and sites. The command will return all Store Services if no IIS VirtualPath or SiteId is specified.StoreFront Stores aggregate desktops and applications, making them available to users.
##Related Commands
*[Add-STFStoreService](Add-STFStoreService)
*[Remove-STFStoreService](Remove-STFStoreService)
*[Set-STFStoreService](Set-STFStoreService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter VirtualPath: The .NET 'System.String' reference type
###System.Int64
Parameter SiteId: The .NET 'System.Int64' value type
###Citrix.StoreFront.Model.Authentication.AuthenticationService
Parameter AuthenticationService: A .NET class representing the configuration of a StoreFront Authentication service
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
##Return Values
###StoreService
A .NET class representing the configuration of a StoreFront Store service
##Examples
###EXAMPLE 1 Get all Stores
```
```
REMARKS

Gets all Stores on the StoreFront server.

```
```
REMARKS

Get the Store at the /Citrix/Store IIS Virtual Path.
