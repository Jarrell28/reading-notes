# Reading Notes

# Class 07 - Bearer Authentication

## 1. Write the following steps in the correct order:

Resource - https://en.wikipedia.org/wiki/Singleton_pattern

-Register your application to get a client_id and client_secret
-Ask the client if they want to sign in via a third party
-Redirect to a third party authentication endpoint
-Receive authorization code
-Make a request to the access token endpoint
-Receive access token
-Make a request to a third-party API endpoint


## 2. What can you do with an authorization code?

Resource - https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/

Authorization code grants your temporary access to a API to see what information the client is requesting.

## 3. What can you do with an access token?

Resource - https://auth0.com/docs/tokens/access-tokens

An access token grants you access to an API

## 4. What’s a benefit of using OAuth instead of your own basic authentication?

-More secure than basic authentication
-Can link your application to other services like sign in with Google,Facebook etc..

## Document the following Vocabulary Terms

- **Client ID** - The client_id is a public identifier for apps. [Resource](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)

- **Client Secret** - The client_secret is a secret known only to the application and the authorization server. [Resource](https://www.oauth.com/oauth2-servers/client-registration/client-id-secret/)

- **Authentication Endpoint** -  Authentication server we make requests to for us to receive an authentication code. 

- **Access Token Endpoint** - Server we make requests to in order to receive an access token.

- **API Endpoint** - A Server we make requests to in order to receive some form of data.

- **Authorization Code** - The authorization code is a temporary code that the client will exchange for an access token. [Resource](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)

- **Access Token** - Access tokens are used in token-based authentication to allow an application to access an API. [Resource](https://auth0.com/docs/tokens/access-tokens)


## Preview

1. Which 3 things had you heard about previously and now have better clarity on? jwt, bearer authentication

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? jwt, patterns for applying jwt
3. 
4. What are you most excited about trying to implement or see how it works? I am curious to learn the different ways we implement jwt in our applications. Specifically how we turn the tokens into sessions
