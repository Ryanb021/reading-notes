# Read 12

## Socket.io

## What is a Web Socket?

- WebSocket is a communications protocol for a persistent, bi-directional, full duplex TCP connection from a user's web browser to a server.

## Describe the Web Socket request/response handshake and what happens once the connection is established.

- A WebSocket connection is initiated by sending a WebSocket handshake request from a browser's HTTP connection to a server to upgrade the connection.

## Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

- Request

## What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

- WebSocket is a technology that enables two-way realtime communication between client and server. In contrast, Socket.IO is a library that provides an abstraction layer on top of WebSockets, making it easier to create realtime applications.
- 
## When would you use Socket.IO?

- When you built real time applications, like Group chat Room, video conferencing, multiplayer games etc.
- If you want server to push data by itself without calling from client.

## When would you use WebSockets?

- Simple posting data to server.
- Real time updating on client side not needed. i.e If you want CRUD you dont have to use sockets.

## OSI Model Explained

- 7 layers of the OSI: Application layer, presentation, session, network, data link, and physical. They allow different operating systems to talk to each other and fully function with each other.

## TCP Handshakes Explained

- Client sends a SYN segment for a connection, server responds with a SYN-ACK, means the server responds with yes, and then the client responds with an ACK, which means that yes he does want to connect.
