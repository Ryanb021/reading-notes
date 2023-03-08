# Read 08

## APIs

## What does REST stand for?

Representational State Transfer

## REST APIs are designed around a ____.

Resource or resources which are any kind of object, data, or service that can be accessed by the client.

## What is an identifier of a resource? Give an example.

A URI that uniquely identifies that resource. Example: https://adventure-works.com/orders/1

## What are the most common HTTP verbs?

POST, GET, PUT, PATCH, and DELETE.

## What should the URIs be based on?

The URI should be composed of keywords that are important to the content of the page. So, if the URI is for a blog post that has a long title, only the words important to the content of the page should be in the URI.

## Give an example of a good URI.

foo://example.com:8042/over/there?name=ferret#nose is a URI containing a scheme name, authority, path, query and fragment. A URI does not need to contain all these components.

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. Reason why chatty APIs are considered poor quality is because requiring multiple network calls will slow down an application. This is because each call contains data overhead (i.e. sender information, headers, authentication) which will slow down an application as well as network latency per each request.

## What status code does a successful GET request return?

200 ok. GET: The requested resource has been fetched and transmitted to the message body.

## What status code does an unsuccessful GET request return?

404: “The requested resource was not found.” This is the most common error message of them all. This code means that the requested resource does not exist, and the server does not know if it ever existed.

## What status code does a successful POST request return?

CREATED 201
Following a POST command, this indicates success, but the textual part of the response line indicates the URI by which the newly created document should be known.

## What status code does a successful DELETE request return?

A successful response of DELETE requests SHOULD be an HTTP response code 200 (OK) if the response includes an entity describing the status.
