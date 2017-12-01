#Get-STFAuthenticationService
Get a StoreFront Authentication service.
##Syntax
```
Get-STFAuthenticationService [-StoreService] <StoreService> [[-VirtualPath] <String>] [[-SiteId] <Int64>] [<CommonParameters>]
Get-STFAuthenticationService [-WebReceiverService] <WebReceiverService> [[-VirtualPath] <String>] [[-SiteId] <Int64>] [<CommonParameters>]
```
##Detailed Description
Gets an Authentication service that matches the supplied criteria. An Authentication service can be retrieved by supplying a linked StoreFront service or service details.
##Related Commands
*[Add-STFAuthenticationService](Add-STFAuthenticationService)
*[Remove-STFAuthenticationService](Remove-STFAuthenticationService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter VirtualPath: The .NET 'System.String' reference type
###System.Int64
Parameter SiteId: The .NET 'System.Int64' value type
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
##Return Values
###AuthenticationService
A .NET class representing the configuration of a StoreFront Authentication service
##Examples
###EXAMPLE 1 Get all Authentication services
```
```
REMARKS

Get all configured Authentication services.
OUTPUT
```
ServiceTokenCertificate : BD1A9D3C2948EC8EFAA153EFEEDB23351F8B80D1
TokenValidationService  : Default Token Validation Service
TokenIssuerUrl          : http://example.storefront.com/Citrix/StoreAuth/auth/v1/token
AuthenticationOptions   : Logging Level:None, Hide Errors:False
Authentication          : TokenServiceId:707a864e-90d2-408a-9111-404e1e705d10, Protocol Choices:7
AuthenticationProtocols : {[citrixAGBasicAuthentication,
                          Citrix.StoreFront.Model.Authentication.NetscalerAuthentication], [formsProtocol,
                          Citrix.StoreFront.Model.Authentication.FormsProtocol], [explicitBL,
                          Citrix.StoreFront.Model.Authentication.ExplicitAuthentication],
                          [delegatedDirectoryClaimFactory,
                          Citrix.StoreFront.Model.Authentication.DelegatedDirectorySettings]}
PnaAuthentication       : Citrix.StoreFront.Model.Authentication.PnaAuthentication
SiteId                  : 1
VirtualPath             : /Citrix/StoreAuth
FriendlyName            : StoreAuth
Hmacs                   : {}
Certificates            : {BD1A9D3C2948EC8EFAA153EFEEDB23351F8B80D1, A02C8391926A23C3547D8D34EB654240FE9BC3FA,
                          333131FF3C2F74E4F786BD3CCBB6967FDFA30795}
TokenManagers           : {Authentication Token Producer, Default Token Validation Service}
Routing                 : StoreAuth:http://example.storefront.com/
ServiceRef              : 1__Citrix_StoreAuth
ConfigurationFile       : C:\inetpub\wwwroot\Citrix\StoreAuth\web.config
TenantId                : 860e9401-39c8-4f2c-928d-34251
```
###EXAMPLE 2 Get an authentication service
```
```
REMARKS

Get an Authentication service configured at a specific virtual path.
OUTPUT
```
ServiceTokenCertificate : BD1A9D3C2948EC8EFAA153EFEEDB23351F8B80D1
TokenValidationService  : Default Token Validation Service
TokenIssuerUrl          : http://example.storefront.com/Citrix/StoreAuth/auth/v1/token
AuthenticationOptions   : Logging Level:None, Hide Errors:False
Authentication          : TokenServiceId:707a864e-90d2-408a-9111-404e1e705d10, Protocol Choices:7
AuthenticationProtocols : {[citrixAGBasicAuthentication,
                          Citrix.StoreFront.Model.Authentication.NetscalerAuthentication], [formsProtocol,
                          Citrix.StoreFront.Model.Authentication.FormsProtocol], [explicitBL,
                          Citrix.StoreFront.Model.Authentication.ExplicitAuthentication],
                          [delegatedDirectoryClaimFactory,
                          Citrix.StoreFront.Model.Authentication.DelegatedDirectorySettings]}
PnaAuthentication       : Citrix.StoreFront.Model.Authentication.PnaAuthentication
SiteId                  : 1
VirtualPath             : /Citrix/StoreAuth
FriendlyName            : StoreAuth
Hmacs                   : {}
Certificates            : {BD1A9D3C2948EC8EFAA153EFEEDB23351F8B80D1, A02C8391926A23C3547D8D34EB654240FE9BC3FA,
                          333131FF3C2F74E4F786BD3CCBB6967FDFA30795}
TokenManagers           : {Authentication Token Producer, Default Token Validation Service}
Routing                 : StoreAuth:http://example.storefront.com/
ServiceRef              : 1__Citrix_StoreAuth
ConfigurationFile       : C:\inetpub\wwwroot\Citrix\StoreAuth\web.config
TenantId                : 860e9401-39c8-4f2c-928d-34251
```
###EXAMPLE 3 Get a Stores Authentication service
```
Get-STFAuthenticationService -StoreService $storeService
```
REMARKS

Get the Authentication service responsible for authenticating a store.
OUTPUT
```
ServiceTokenCertificate : BD1A9D3C2948EC8EFAA153EFEEDB23351F8B80D1
TokenValidationService  : Default Token Validation Service
TokenIssuerUrl          : http://example.storefront.com/Citrix/StoreAuth/auth/v1/token
AuthenticationOptions   : Logging Level:None, Hide Errors:False
Authentication          : TokenServiceId:707a864e-90d2-408a-9111-404e1e705d10, Protocol Choices:7
AuthenticationProtocols : {[citrixAGBasicAuthentication,
                          Citrix.StoreFront.Model.Authentication.NetscalerAuthentication], [formsProtocol,
                          Citrix.StoreFront.Model.Authentication.FormsProtocol], [explicitBL,
                          Citrix.StoreFront.Model.Authentication.ExplicitAuthentication],
                          [delegatedDirectoryClaimFactory,
                          Citrix.StoreFront.Model.Authentication.DelegatedDirectorySettings]}
PnaAuthentication       : Citrix.StoreFront.Model.Authentication.PnaAuthentication
SiteId                  : 1
VirtualPath             : /Citrix/StoreAuth
FriendlyName            : StoreAuth
Hmacs                   : {}
Certificates            : {BD1A9D3C2948EC8EFAA153EFEEDB23351F8B80D1, A02C8391926A23C3547D8D34EB654240FE9BC3FA,
                          333131FF3C2F74E4F786BD3CCBB6967FDFA30795}
TokenManagers           : {Authentication Token Producer, Default Token Validation Service}
Routing                 : StoreAuth:http://example.storefront.com/
ServiceRef              : 1__Citrix_StoreAuth
ConfigurationFile       : C:\inetpub\wwwroot\Citrix\StoreAuth\web.config
TenantId                : 860e9401-39c8-4f2c-928d-34251102b840
```