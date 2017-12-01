#Start-STFServerGroupJoin
Start the Server Group join process
##Syntax
```
Start-STFServerGroupJoin [-IsAuthorizingServer] <SwitchParameter> [<CommonParameters>]
```
##Detailed Description
Start the Server Group join process.
##Related Commands
*[Stop-STFServerGroupJoin](Stop-STFServerGroupJoin)
*[Remove-STFServerGroupMember](Remove-STFServerGroupMember)
*[Wait-STFServerGroupJoin](Wait-STFServerGroupJoin)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter AuthorizerHostName: The .NET 'System.String' reference type
###System.String
Parameter Passcode: The .NET 'System.String' reference type
###System.Management.Automation.SwitchParameter
Parameter IsAuthorizingServer: The .NET 'System.Management.Automation.SwitchParameter' value type
##Return Values
###ClusterPasscodeResponse ClusterResponse
The .NET 'Citrix.DeliveryServices.ClusterService.Contract.ClusterPasscodeResponse' reference type
The .NET 'Citrix.DeliveryServices.ClusterService.Contract.ClusterResponse' reference type
##Notes
When executed on a joining server the authorizing server and passcode is required.
##Examples
###EXAMPLE 1 Authorize a server to join
```
Write-Host 'Use the Passcode to join to this server'
```
REMARKS

Starts the join process providing a pass code that can be taken to a 'joiner' server so it can join to the authorizing
server.
OUTPUT
```
     
--------                                                                     ------ -------------                      
     
83226368                                                              PasscodeReady Passcode for authorization.

Use the Passcode to join to this server
```
###EXAMPLE 2 Join an authorizing server
```
```
REMARKS

Join the authorizing server 'serverA' using the passcode 12345678 that was generated for it.
