#Enable-STFStorePna
Enable PNA (XenApp Services) for a Store
##Syntax
```
```
##Detailed Description
Enable PNA (XenApp Services) for a Store so it can be accessed clients using the PNA protocol.
##Related Commands
*[Disable-STFStorePna](Disable-STFStorePna)
*[Clear-STFDefaultPnaStore](Clear-STFDefaultPnaStore)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###System.Management.Automation.SwitchParameter
Parameter AllowUserPasswordChange: The .NET 'System.Management.Automation.SwitchParameter' value type
###Citrix.StoreFront.Model.Store.LogonMethod
Parameter LogonMethod: The .NET 'Citrix.StoreFront.Model.Store.LogonMethod' value type
###System.Management.Automation.SwitchParameter
Parameter DefaultPnaService: The .NET 'System.Management.Automation.SwitchParameter' value type
##Return Values
##Examples
###EXAMPLE 1 Enable PNA for the only Store
```
Enable-STFStorePna $storeService -AllowUserPasswordChange -DefaultPnaService
```
REMARKS

Enable PNA on the only Store, allow users to change password and make it the deafult PNA site.
