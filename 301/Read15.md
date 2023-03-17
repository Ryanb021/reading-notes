# Read 15

# Authentication

## What is OAuth?

- OAuth is an open-standard authorization protocol or framework that provides applications the ability for “secure designated access.”

## Give an example of what using OAuth would look like.

- For example, you can tell Facebook that it's OK for ESPN.com to access your profile or post updates to your timeline without having to give ESPN your Facebook password.

## How does OAuth work? What are the steps that it takes to authenticate the user?

- Step 1 – The User Shows Intent
- Step 2 – The Consumer Gets Permission
- Step 3 – The User Is Redirected to the Service Provider
- Step 4 – The User Gives Permission
- Step 5 – The Consumer Obtains an Access Token
- Step 6 – The Consumer Accesses the Protected Resource

## What is OpenID?

- OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords. You may choose to associate information with your OpenID that can be shared with the websites you visit, such as a name or email address.

## What is the difference between authorization and authentication?

- The explanation of the difference between OpenID, OAuth, OpenID Connect: OpenID is a protocol for authentication while OAuth is for authorization. Authentication is about making sure that the guy you are talking to is indeed who he claims to be. Authorization is about deciding what that guy should be allowed to do.

## What is Authorization Code Flow?

- The Authorization Code Flow is used by server-side applications that are capable of securely storing secrets, or by native applications through Authorization Code Flow with PKCE. The OIDC-conformant pipeline affects the Authorization Code Flow in the following areas: Authentication request. Authentication response.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

- The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.

## What is Implicit Flow with Form Post?

- Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

## What is Client Credentials Flow?

- In the client credentials flow, permissions are granted directly to the application itself by an administrator. When the app presents a token to a resource, the resource enforces that the app itself has authorization to perform an action since there is no user involved in the authentication.

## What is Device Authorization Flow?

- The OAuth 2.0 Device Authorization Grant (formerly known as the Device Flow) is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token. This is commonly seen on Apple TV apps, or devices like hardware encoders that can stream video to a YouTube channel.

## What is Resource Owner Password Flow?

- The Resource Owner Password Flow is used by highly-trusted applications to provide active authentication. Unlike the authorization code and implicit grants, this authentication mechanism does not redirect users to Auth0. It authenticates users with a single request, exchanging their password credentials for a token.
