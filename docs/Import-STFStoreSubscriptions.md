#Import-STFStoreSubscriptions
Import subscriptions from a given Store
##Syntax
```
Import-STFStoreSubscriptions [-FilePath] <String> [-StoreService] <StoreService> [-FilePath] <String> [<CommonParameters>]
```
##Detailed Description
Import user subscriptions to a Store from a csv formatted text file.
##Related Commands
*[Export-STFStoreSubscriptions](Export-STFStoreSubscriptions)
*[Restore-STFStoreSubscriptions](Restore-STFStoreSubscriptions)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###System.String
Parameter FilePath: The .NET 'System.String' reference type
###System.Int32
Parameter ChunkSize: The .NET 'System.Int32' value type
##Return Values
##Notes
The cmdlet appends the entries to the existing data.
##Examples
###EXAMPLE 1 Import subscriptions
```
Import-STFStoreSubscriptions -Store $store -FilePath "$env:userprofile\desktop\Export.txt"
```
REMARKS

Import subscriptions into the only configured Store.
