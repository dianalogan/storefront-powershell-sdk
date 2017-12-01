#Disable-STFStorePna
Disable PNA (XenApp Services) for a Store
##Syntax
```
```
##Detailed Description
Disable PNA (XenApp Services) for a Store so it cannot be accessed clients using the PNA protocol.
##Related Commands
*[Enable-STFStorePna](Enable-STFStorePna)
*[Clear-STFDefaultPnaStore](Clear-STFDefaultPnaStore)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
##Return Values
##Examples
###EXAMPLE 1 Disable PNA for the only Store
```
Disable-STFStorePna -StoreService $storeService
```
REMARKS

Disables PNA for the only configured Store service.
