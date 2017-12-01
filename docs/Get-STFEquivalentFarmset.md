#Get-STFEquivalentFarmset
Get the EquivalentFarmSet for a UserFarmMapping
##Syntax
```
```
##Detailed Description
Get the EquivalentFarmSets configured for a UserFarmMapping or a specific EquivalentFarmSet matching the supplied name.
##Related Commands
*[New-STFEquivalentFarmset](New-STFEquivalentFarmset)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.UserFarmMapping
Parameter UserFarmMapping: The .NET 'Citrix.StoreFront.Model.Store.UserFarmMapping' reference type
###System.String
Parameter Name: The .NET 'System.String' reference type
##Return Values
###EquivalentFarmSet
The .NET 'Citrix.StoreFront.Model.Store.EquivalentFarmSet' reference type
##Examples
###EXAMPLE 1 Get all EquivalentFarmSets
```
```
REMARKS

Gets all existing EquivalentFarmSet on the $UserFarmMapping object.

```
```
REMARKS

Gets the EUMapping from the UserFarmMapping $UserFarmMapping.
