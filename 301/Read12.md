# Read 12

# Status Codes based on REST methods

## 100’s =
These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.

## 200’s =
These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

## 300’s =
These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

## 400’s =
These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

## 500’s =
These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

## What is a status code 202?

The request has been accepted for processing, but the processing has not been completed.

## What is a status code 308?

Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers.

## What code would you use if an update didn’t return data to a client?

204 No Content - A proper code for updates that don't return data to the client.

## What code would you use if a resource used to exist but no longer does?

The HyperText Transfer Protocol (HTTP) 410 Gone client error response code indicates that access to the target resource is no longer available at the origin server and that this condition is likely to be permanent.

## What is the ‘Forbidden’ status code?

The HTTP 403 Forbidden response status code indicates that the server understands the request but refuses to authorize it. This status is similar to 401 , but for the 403 Forbidden status code, re-authenticating makes no difference.

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

So we don't publish it and make it public when psuhed to GitHub.

## What is middleware?

A request handler with access to the application's request-response cycle is known as middleware. It's a function that holds the request object, the response object, and the middleware function. Middleware can also send the response to the server before the request.Feb

## What does app.use(express.json()) do?

## What is the difference between PUT and PATCH?

PUT - is used for modifying existing resource (Previously POSTED). On the other hand the PATCH request is used to update some portion of existing resource.

## What does a 500 error status code mean?

The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.

## What is the difference between a status 200 and a status 201?

200: “Everything is OK.” This is the code that is delivered when a web page or resource acts exactly the way it's expected to. 201: “Created.” The server has fulfilled the browser's request, and as a result, has created a new resource.

