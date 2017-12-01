#Get-STFRoamingServiceRecord
Get the Service Record
##Syntax
```
```
##Detailed Description
Get the Service record for a specific or all Stores.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###Citrix.StoreFront.Model.Roaming.RoamingService
Parameter RoamingService: A .NET class representing the configuration of a StoreFront Roaming service
##Return Values
###ServiceRecords
The .NET 'Citrix.StoreFront.Model.Roaming.ServiceRecords' reference type
##Examples
###EXAMPLE 1 Get Service record for a specific Store
```
Get-STFRoamingServiceRecord -StoreService $store
```
REMARKS

Get the service record used for accessing the specified Store service
