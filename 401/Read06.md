# Read 06

## Authentication

## Explain to a non-technical friend how you would safely hash and store a password.

- Safely hashing a password if I had to explain it to a non-technical friend, are like code words. Code words will only be known between the two of us. Like the user and the computer. In order to protect our code words, we keep it to ourselves or we use random fake codewords to mislead other who tries to steal our code word. Storing it will be in our heads.

## What is Bcrypt?

- Bcrypt is a password hashing algorithm designed by Niels Provos and David Mazières based on the Blowfish cipher. The name “bcrypt” is made of two parts: b and crypt, where b stands for Blowfish and crypt is the name of the hashing function used by the Unix password system.

## Why might you use something like Bcrypt?

- The bcrypt hashing function allows us to build a password security platform that scales with computation power and always hashes every password with a salt.

## What is Basic Authentication?

- HTTP basic authentication is a simple challenge and response mechanism with which a server can request authentication information (a user ID and password) from a client. The client passes the authentication information to the server in an Authorization header. The authentication information is in base-64 encoding.

## What properties are necessary in the header of a Basic Auth request?

- Basic authentication is a very simple authentication scheme that is built into the HTTP protocol. The client sends HTTP requests with the Authorization header that contains the Basic word followed by a space and a base64-encoded username:password string.

## How are username:password in Basic Auth encoded?

- Basic Authentication sends a Base64 encoded string that contains a user name and password for the client via HTTP headers. Base64 is not a form of encryption and should be considered the same as sending the user name and password in clear text.

## Define the authentication process to a non-technical recruiter.

- Authentication process if I had to expalin it to a non technical friend is like applying for a driver's license. We are required to provide information to authenticate that it is the actual individual applying for the driver's license.

## How should your error messaging respond (both HTTP and HTML)? Why?

- In a generic manner. The objective is to prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.

## Looking ahead at this module’s course schedule, What do you look forward to learning?

- Everything. I am still confused.

## What are your learning goals after reading and reviewing the class README?

- Is to be as good or better than the instructors and TAs.
