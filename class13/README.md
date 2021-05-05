
# Reading Notes

# Class 12 - Socket.io

## 1. What does it mean that web sockets are bidirectional? Why is this useful?

[Resource](https://www.amx.com/en/site_elements/benefits-and-applications-of-websockets)

This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time. 


## 2. Does socket.io use HTTP? Why?

[Resource](https://www.amx.com/en/site_elements/benefits-and-applications-of-websockets)

socket.io uses HTTP for the initial handshake connection between client and server. Afterwards, the connection is kept alive via a ping-pong process in which the server continuously pings the client for a response.

## 3. What happens when a client emits an event?

If the server is listening for the event, it will fire the callback function

## 4. What happens when a server emits an event?

If the client is listening for the event and it will fire the callback function

## 5. What happens if a client “misses” an event?

[Resource](https://stackoverflow.com/questions/32816290/what-happens-with-unhandled-socket-io-events)

The client will ignore the event if it does not have a handler for that specific event

## 6. How can we mitigate this?

If the client does not have a handler for the event, you could create one or have the events only emit to clients that it needs to

## Document the following Vocabulary Terms

- **Socket** - Sockets allow communication between two different processes on the same or different machines.[Resource](https://www.tutorialspoint.com/unix_sockets/what_is_socket.htm)

- **Web Socket** - WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.  [Resource](https://en.wikipedia.org/wiki/WebSocket)

- **Socket.io** -Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server. [Resource](https://socket.io/docs/v4/index.html)

- **Client** - A client is anything that makes a requests to a server

- **Server** - A server hosts data and receives requests from clients and responds appropriately

- **OSI Model** -The Open Systems Interconnection model (OSI model) is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology. Its goal is the interoperability of diverse communication systems with standard communication protocols. [Resource](https://en.wikipedia.org/wiki/OSI_model)

- **TCP Model** - TCP/IP Model helps you to determine how a specific computer should be connected to the internet and how data should be transmitted between them. It helps you to create a virtual network when multiple computer networks are connected together. The purpose of TCP/IP model is to allow communication over large distances. [Resource](https://www.guru99.com/tcp-ip-model.html)

- **TCP** - Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite. TCP is connection-oriented, and a connection between client and server is established before data can be sent. [Resource](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)

- **UDP** - User Datagram Protocol (UDP) is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network. Prior communications are not required in order to set up communication channels or data paths. [Resource](https://en.wikipedia.org/wiki/User_Datagram_Protocol)

- **Packets** - a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data; the latter is also known as the payload. [Resource](https://en.wikipedia.org/wiki/Network_packet)

## Preview

1. Which 3 things had you heard about previously and now have better clarity on? Socket.io, Rooms, Namespaces

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Socket.io

3. What are you most excited about trying to implement or see how it works? Excited about learning more of Socket.io


