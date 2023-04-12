# Read 07

## Bearer Authorization

## What is a JSON Web Token (JWT)?

- JSON web token (JWT), pronounced "jot", is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. Again, JWT is a standard, meaning that all JWTs are tokens, but not all tokens are JWTs.
- 
## When should we use JSON Web Tokens?

- Authorization and Information Exchange. JWTs are a good way of securely transmitting information between parties because they can be signed, which means you can be sure that the senders are who they say they are. Additionally, the structure of a JWT allows you to verify that the content hasn't been tampered with.

## Claims are expected in which structural component of a JWT?

- The second part of the token is the payload, which contains the claims. Claims are statements about an entity (typically, the user) and additional data. 

## If I get a JWT and I can decode the payload, how can we call that secure?

- Only JWT's privateKey, which is on your server will decrypt the encrypted JWT. Those who know the privateKey will be able to decrypt the encrypted JWT. Hide the privateKey in a secure location in your server and never tell anyone the privateKey. JWTs are not always encrypted.
- 
## If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

- Public and private key.
- 
## Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

- Concatenate is another word for join. To send it your joined content and secret securely, you have to hash it. Like hash browns.

## Why use JWT?

- JWTs are a good way of securely transmitting information between parties because they can be signed, which means you can be sure that the senders are who they say they are. Additionally, the structure of a JWT allows you to verify that the content hasn't been tampered with.

## JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

- I would say to a non-technical friend that JWT being compact and self contained is like a portable safe deposit box. It's compact, you can take it with you, and self-secure. No one can access it except you.

## What are the three components (the structure) of a JWT signature?

- A header, payload, and signature. The header typically consists of two parts: the type of the token, which is JWT, and the algorithm that is used, such as HMAC SHA256 or RSA SHA256. It is Base64Url encoded to form the first part of the JWT.
