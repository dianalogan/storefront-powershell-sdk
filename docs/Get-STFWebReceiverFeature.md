#Get-STFWebReceiverFeature
Gets the web receiver features
##Syntax
```
```
##Detailed Description
Gets the feature instances that have been added to the specified WebReceiver service.
##Related Commands
*[Add-STFWebReceiverFeature](Add-STFWebReceiverFeature)
*[Remove-STFWebReceiverFeature](Remove-STFWebReceiverFeature)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter Name: The .NET 'System.String' reference type
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
##Return Values
##Examples
###EXAMPLE 1 Get all WebReceiver feature instances.
```
Get-STFWebReceiverFeature -WebReceiverService $rfw
```

```
Get-STFWebReceiverFeature -Name U2FReceiverPlugin -WebReceiverService $rfw
```
