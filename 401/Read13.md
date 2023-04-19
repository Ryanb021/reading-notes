# Read 13

## Message Queues

## Explain to a non-technical recruiter what the Chat Example (above) does.

- If I would explain the chat example to a non-technical friend, I would say that it captures a message from client side and send the message to everyone in the same network.

## What proof of life are we getting on the backend from the above app?

- Proof of life is to listen on the connection event for incoming sockets and log it to the console.

## Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

-  Broadcast.

## What is a room and how might a room be useful?

- A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

## How do you join a room?

- io.on(“connection”, (socket) => { socket.join(“some room”); });

## how do you leave a room?

- socket.on(“disconnect”, () => { // socket.rooms.size === 0 });

## What is a Namespace and what does it allow you to do?

- A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.

## Each namespace potentially has its own what? (hint: 3 things)

- Event handlers, rooms, middlewares.

## Discuss a possible use case for separate namespaces

- Namespaces allow the developer to create separate organization units that can be used to hold multiple values, like properties, classes, types, and interfaces.
