#Set-STFWebReceiverResourcesService
Set the WebReceiver Resources Service settings
##Syntax
```
```
##Detailed Description
Set the WebReceiver Resources Service settings.
##Related Commands
*[Get-STFWebReceiverResourcesService](Get-STFWebReceiverResourcesService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
###System.Boolean
Parameter PersistentIconCacheEnabled: The .NET 'System.Boolean' value type
###System.Int32
Parameter IcaFileCacheExpiry: The .NET 'System.Int32' value type
###System.Int32
Parameter IconSize: The .NET 'System.Int32' value type
###System.Boolean
Parameter ShowDesktopViewer: The .NET 'System.Boolean' value type
##Return Values
##Examples
###EXAMPLE 1 Configure the Desktop viewer
```
Set-STFWebReceiverResourcesService -WebReceiverService $webReceiver -ShowDesktopViewer $true
```
REMARKS

Set the Desktop Viewer to be shown for the WebReceiver located at /Citrix/StoreWeb.
