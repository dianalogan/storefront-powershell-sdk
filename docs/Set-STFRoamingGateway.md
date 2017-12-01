#Set-STFRoamingGateway
Update the settings on a Gateway
##Syntax
```
Set-STFRoamingGateway [-Name] <String> [[-LogonType] <UsedForHDXOnly | Domain | RSA | DomainAndRSA | SMS | GatewayKnows | SmartCard | None>] [[-SmartCardFallbackLogonType] <UsedForHDXOnly | Domain | RSA | DomainAndRSA | SMS | GatewayKnows | SmartCard | None>] [[-Version] <Version10_0_69_4 | Version9x>] [[-GatewayUrl] <Uri>] [[-CallbackUrl] <Uri>] [[-SessionReliability] <Boolean>] [[-RequestTicketTwoSTAs] <Boolean>] [[-SubnetIPAddress] <String>] [[-SecureTicketAuthorityUrls] <Uri[]>] [[-PassThru] <SwitchParameter>] [[-GslbUrl] <Uri>] [[-RoamingService] <RoamingService>] [<CommonParameters>]
```
##Detailed Description
Update the settings of an existing Gateway from the global gateways list.
##Related Commands
*[Add-STFRoamingGateway](Add-STFRoamingGateway)
*[Get-STFRoamingGateway](Get-STFRoamingGateway)
*[Remove-STFRoamingGateway](Remove-STFRoamingGateway)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Roaming.RoamingGateway
Parameter Gateway: The .NET 'Citrix.StoreFront.Model.Roaming.RoamingGateway' reference type
###System.String
Parameter Name: The .NET 'System.String' reference type
###Citrix.StoreFront.Model.Roaming.GatewayLogonType
Parameter LogonType: The .NET 'Citrix.StoreFront.Model.Roaming.GatewayLogonType' value type
###Citrix.StoreFront.Model.Roaming.GatewayLogonType
Parameter SmartCardFallbackLogonType: The .NET 'Citrix.StoreFront.Model.Roaming.GatewayLogonType' value type
###Citrix.StoreFront.Model.Roaming.GatewayVersion
Parameter Version: The .NET 'Citrix.StoreFront.Model.Roaming.GatewayVersion' value type
###System.Uri
Parameter GatewayUrl: The .NET 'System.Uri' reference type
###System.Uri
Parameter CallbackUrl: The .NET 'System.Uri' reference type
###System.Boolean
Parameter SessionReliability: The .NET 'System.Boolean' value type
###System.Boolean
Parameter RequestTicketTwoSTAs: The .NET 'System.Boolean' value type
###System.String
Parameter SubnetIPAddress: The .NET 'System.String' reference type
###System.Uri[]
Parameter SecureTicketAuthorityUrls: The .NET 'System.Uri' reference type
###System.Management.Automation.SwitchParameter
Parameter PassThru: The .NET 'System.Management.Automation.SwitchParameter' value type
###System.Uri
Parameter GslbUrl: The .NET 'System.Uri' reference type
###Citrix.StoreFront.Model.Roaming.RoamingService
Parameter RoamingService: A .NET class representing the configuration of a StoreFront Roaming service
##Return Values
##Examples
###EXAMPLE 1 Update Gateway
```
```
REMARKS

Updates the Gateway to use Domain logon.
