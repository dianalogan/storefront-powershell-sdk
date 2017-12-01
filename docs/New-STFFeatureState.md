#New-STFFeatureState
Creates and returns a new FeatureState object
##Syntax
```
```
##Detailed Description
Creates and returns a new FeatureState object
##Related Commands
*[Add-STFFeatureState](Add-STFFeatureState)
*[Get-STFFeatureState](Get-STFFeatureState)
*[Get-STFFeatureStateNames](Get-STFFeatureStateNames)
*[New-STFFeatureStateProperty](New-STFFeatureStateProperty)
*[Remove-STFFeatureState](Remove-STFFeatureState)
*[Clear-STFFeatureStates](Clear-STFFeatureStates)
*[Reset-STFFeatureData](Reset-STFFeatureData)
*[Set-STFFeatureState](Set-STFFeatureState)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter Name: The .NET 'System.String' reference type
###System.Boolean
Parameter IsEnabled: The .NET 'System.Boolean' value type
###System.Collections.Hashtable
Parameter Properties: The .NET 'System.Collections.Hashtable' reference type
##Return Values
###FeatureState
The .NET 'Citrix.DeliveryServices.Framework.FeatureToggle.FeatureState' reference type
##Examples
###EXAMPLE 1 Creates a new FeatureState object
```
```
REMARKS

Creates a new FeatureState object with properties and status set to enabled
OUTPUT
```
----                       --------- ----------                
something                  True      {Property1, Property2}
```
###EXAMPLE 2 Creates a new FeatureState object
```
```
REMARKS

Creates a new FeatureState object without properties and status set to enabled
OUTPUT
```
----                       --------- ----------                
something                  True      {}
```
###EXAMPLE 3 Creates a new FeatureState object
```
```
REMARKS

Creates a new FeatureState object without properties and status set to disabled
OUTPUT
```
----                       --------- ----------                
something                  False     {}
```