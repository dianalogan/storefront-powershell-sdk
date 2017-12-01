#New-STFUserFarmMappingGroup
Create a new UserFarmMapping group
##Syntax
```
New-STFUserFarmMappingGroup [-AllUsers] <SwitchParameter> [<CommonParameters>]
```
##Detailed Description
Create a group to which a UserFarmMapping can be assigned. A UserFarmMapping is used to configure a specified group of users to use the EquivalentFarmSets defined within the UserFarmMapping. A UserFarmMapping can be used to partition users between defferent XenApp\XenDesktop servers.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter GroupName: The .NET 'System.String' reference type
###System.String
Parameter AccountSid: The .NET 'System.String' reference type
###System.Management.Automation.SwitchParameter
Parameter AllUsers: The .NET 'System.Management.Automation.SwitchParameter' value type
##Return Values
###Hashtable
The .NET 'System.Collections.Hashtable' reference type
##Examples
###EXAMPLE 1 New UserFarmMappingGroup for all user
```
```
REMARKS

Creates a new UserMappingGroup for a UserFarmMapping.
