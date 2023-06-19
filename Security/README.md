
**Authentication** 

    Protocols - OIDC, SAML

    OIDC uses OAuth2
    https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc 
    [https://openid.net/connect/](https://openid.net/developers/how-connect-works/)
    https://oauth.net/articles/authentication/

    Tokens - ID token, Access token, Refresh token
    ID token vs userInfo endpoint
    https://stackoverflow.com/questions/46212029/id-token-or-userinfo-for-identity-assertion

**Authorization**

    OAuth, OAuth2
    OAuth grant types
    https://oauth.net/2/grant-types/
    https://auth0.com/docs/get-started/applications/application-grant-types

    Client credentials vs Implicit workflow
    https://stackoverflow.com/questions/16321455/what-is-the-difference-between-the-oauth-authorization-code-and-implicit-workflo
    PKCE with authorization Code
    https://christianlydemann.com/implicit-flow-vs-code-flow-with-pkce/

    scopes
    https://auth0.com/docs/get-started/apis/scopes/openid-connect-scopes

    State
    https://auth0.com/docs/secure/attack-protection/state-parameters
    State vs PKCE
    https://stackoverflow.com/questions/71349839/code-challange-vs-state-parameter-in-oauth-what-is-the-difference



https://stackoverflow.com/questions/33702826/oauth-authorization-vs-authentication

https://developer.okta.com/blog/2019/01/23/nobody-cares-about-oauth-or-openid-connect#why-openid-connect-exists

**Tokens**

    Types of tokens - ID token, access token and refresh token
    Token format - JWT, opaque
    ID token is JWT or opaque
    Access token can be opaque 
    https://auth0.com/docs/secure/tokens/access-tokens
    
    ID token vs Access token
    https://developer.okta.com/docs/guides/validate-access-tokens/dotnet/main/
    https://auth0.com/blog/id-token-access-token-what-is-the-difference/

    Access token vs Refresh token
    https://stackoverflow.com/questions/34931052/how-does-a-short-lived-access-token-add-security

    Access and refresh tokens are not stored in browser
    They are kept at server side
    https://medium.com/smallcase-engineering/web-security-access-token-in-url-79366a2bcb49 
    Access token is self validating and has a very short expiration time

    API token
    API token vs Access token
    https://docs.vmware.com/en/VMware-Cloud-services/services/Using-VMware-Cloud-Services/GUID-1EEC504F-CFE5-4030-8DCB-1201CECF8B45.html#:~:text=The%20difference%20is%20that%20API,service%20involved%20in%20the%20interaction





OIDC - ID token, , claims




Session

Cookies - [Samesite attribute](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie/SameSite)

Federated Identity, SSO

Basic use case - An application can use gmail to sign in (login) a user 

https://stackoverflow.blog/2021/10/06/best-practices-for-authentication-and-authorization-for-rest-apis/


Firewall vs Proxy

