#Get-STFStoreFarmConfiguration
Get common Store farm options
##Syntax
```
```
##Detailed Description
Get the details of an existing farm.
##Related Commands
*[Set-STFStoreFarmConfiguration](Set-STFStoreFarmConfiguration)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
##Return Values
###Farm
A .NET class representing the configuration of a Farm in StoreFront Store service
##Examples
###EXAMPLE 1 Get farm options
```
Get-STFStoreFarmConfiguration -StoreService $store
```
REMARKS

Get the only configured farm options.
