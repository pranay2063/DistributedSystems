
**Authentication** 

    Authentication is about who the user is or validation of user identity
    Federated Identity, SSO
    SSO is the ability of users to sign in to multiple apps with the same set of credentials
    Federation is an extension of SSO where sign in can be done for apps belonging to different organizations 
    Authentication mechanisms - multi-factor, username and password, seamless
    
    Protocols - OIDC, SAML

    OIDC uses OAuth2
    https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc 
    https://openid.net/developers/how-connect-works/
    https://oauth.net/articles/authentication/

    Tokens - ID token, Access token, Refresh token
    ID token vs userInfo endpoint
    https://stackoverflow.com/questions/46212029/id-token-or-userinfo-for-identity-assertion

    OAuth scope is set as openid for OIDC

    Java pac4j
    https://www.pac4j.org/docs/main-concepts-and-components.html
    https://www.pac4j.org/docs/index.html
    https://www.pac4j.org/gettingstarted.html
    https://www.pac4j.org/docs/clients/openid-connect.html
    

**Authorization**

    Authorization is about whether a user or client can access a resource
    OAuth, OAuth2
    OAuth grant types
    https://oauth.net/2/grant-types/
    https://auth0.com/docs/get-started/applications/application-grant-types

    Client credentials vs Implicit workflow
    https://stackoverflow.com/questions/16321455/what-is-the-difference-between-the-oauth-authorization-code-and-implicit-workflo
    PKCE with authorization Code
    https://christianlydemann.com/implicit-flow-vs-code-flow-with-pkce/

    Scope
    Scope returns claims
    Scope is set as openid for OIDC
    https://auth0.com/docs/get-started/apis/scopes/openid-connect-scopes

    State
    https://auth0.com/docs/secure/attack-protection/state-parameters
    State vs PKCE
    https://stackoverflow.com/questions/71349839/code-challange-vs-state-parameter-in-oauth-what-is-the-difference


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
    https://shorturl.at/dqrQT


**Related Information**

        Session
        
        Cookies 
        Samesite attribute
        https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie/SameSite
        
        https://stackoverflow.com/questions/33702826/oauth-authorization-vs-authentication
        https://developer.okta.com/blog/2019/01/23/nobody-cares-about-oauth-or-openid-connect#why-openid-connect-exists
        
        https://stackoverflow.blog/2021/10/06/best-practices-for-authentication-and-authorization-for-rest-apis/

        Identity provider 
        Okta, PingFederate, Azure Active Directory etc

        Firewall vs Proxy
        Firewall allows/filters packets in the network
        Proxy routes incoming/outgoing traffic to an organization
        Forward proxy and Reverse proxy

        Basic use case - An application can use gmail to sign in (login) a user 














