# Read 03

## Express REST API

## Classes are a template for creating ____.

- Objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are unique to classes.
- 
## Can a class declaration be hoisted?

- Classes do not get hoisted, and cannot be read or accessed before their declaration.

## How would you describe a constructor and contextual “this” to a non-technical friend?

- THIS is a reference to an object.

## Within Express, what does routing refer to?

- Routing refers to how an application's endpoints (URIs) respond to client A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
requests. 

## What is the difference between a route path and a route method?

- Routing refers to how an application’s endpoints (URIs) respond to client requests. A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.

## When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

- If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Or if you have more than 2 arguments.

## What is an Express Router?

- Express Routers are a way to organize your Express application such that your primary app. js file does not become bloated and difficult to reason about.

## By what mean do we initialize express.Router() in an express server?

- The express.Router() function is used to create a new router object. This function is used when you want to create a new router object in your program to handle requests. 

## What do we use route middleware for?

- Middleware functions access the HTTP request and response objects. They either terminate the HTTP request or forward it for further processing to another middleware function. We can add middleware functions to all the routes by using the app.
