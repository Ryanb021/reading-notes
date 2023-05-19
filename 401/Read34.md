# Read 34

# API Integration

### Explain the different between a query string parameter and a path parameter.

- Path params are used to identify a specific resource, while query params are used to filter and sort the data.

### What would our API URL with a path id parameter be given the following information:

- Domain: http://our-site.com
- v3
- model name: stuff
- id: things

- *http://our-site.com/v3/stuff/things*

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

- Server talking to the database. Like your Father talking to your son.

### Describe how you would use middleware to implement basic and bearer auth.

- Auth middleware will be nothing more than a piece of code that will validate an authentication token and will try to resolve the user against that authentication token. It will be just a piece of code that will be attached to some endpoints in the routes or place from where the data for the endpoint is being returned.

### Describe the handshake necessary to implement OAuth.

- The OAuth 2.0 handshake involves the Authorization request and the access token request. The access token is the end goal because it allows the app to finally access the user's information.

### Describe how Role Based Access Control works to a non-technical friend.
