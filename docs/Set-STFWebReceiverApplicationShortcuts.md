#Set-STFWebReceiverApplicationShortcuts
Set the WebReceiver application shortcuts
##Syntax
```
```
##Detailed Description
Set the WebReceiver trusted Urls for application shortcuts.
##Related Commands
*[Get-STFWebReceiverApplicationShortcuts](Get-STFWebReceiverApplicationShortcuts)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
###System.Boolean
Parameter PromptForUntrustedShortcuts: The .NET 'System.Boolean' value type
###System.Uri[]
Parameter TrustedUrls: The .NET 'System.Uri' reference type
###System.Uri[]
Parameter GatewayUrls: The .NET 'System.Uri' reference type
##Return Values
##Examples
###EXAMPLE 1 Configure the Application Shortcuts
```
Set-STFWebReceiverApplicationShortcuts -WebReceiverService $webReceiver -TrustedUrls "https://mycompany.net"
```
REMARKS

Set the WebReceiver trusted urls for shortcuts that users can launch.
