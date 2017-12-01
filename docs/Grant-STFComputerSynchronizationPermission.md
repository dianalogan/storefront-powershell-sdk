#Grant-STFComputerSynchronizationPermission
Grant a computer synchronization permissions
##Syntax
```
```
##Detailed Description
Grant a StoreFront server on the same domain permission to synchronize from the local Subscription Store.
##Related Commands
*[Revoke-STFComputerSynchronizationPermission](Revoke-STFComputerSynchronizationPermission)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String[]
Parameter RemoteServer: The .NET 'System.String' reference type
##Return Values
##Notes
Restarts the Citrix Subscription Store Service to read new settings.
##Examples
###EXAMPLE 1 Grant multiple server synchronization permissions
```
```
REMARKS

Grant StoreFront servers APACSF1 and APACSF2 from the APAC StoreFront group permissions to synchronize.
