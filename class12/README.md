# Reading Notes

# Class 12 - Socket.io

## 1. What is the benefit of transforming data into packets?

[Resource](https://en.wikipedia.org/wiki/Packet_switching#:~:text=Packet%20switching%20is%20used%20to,to%20increase%20robustness%20of%20communication.)

To optimize the use of the channel capacity available in digital telecommunication networks, such as computer networks, and minimize the transmission latency (the time it takes for data to pass across the network), and to increase robustness of communication.


## 2. UDP is often refereed to as a connectionless protocol. Why is this?

[Resource](https://en.wikibooks.org/wiki/Communication_Networks/TCP_and_UDP_Protocols/UDP)

UDP doesn't establish a connection before sending data, it just sends the data.

## 3. Can a socket server application have multiple socket connections?

[Resource](https://www.gnu.org/software/libc/manual/html_node/Accepting-Connections.html)

A socket that has been established as a server can accept connection requests from multiple clients

## 4. Can a socket connection application be connected to multiple socket servers?

Yes, you can establish a connection to multple socket servers from a single client.

## 5. Can an application be both a socket server and a socket connection?

[Resource](https://www.quora.com/Can-you-make-a-client-socket-and-a-server-socket-in-one)

You can make a a socket client and socket server within a single application by using two different ports or if the socket won't be using the same port at the same time


## Document the following Vocabulary Terms

- **Observer Pattern** - a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.[Resource](https://en.wikipedia.org/wiki/Observer_pattern)

- **Listener** - An event listener is a procedure or function in a computer program that waits for an event to occur. [Resource](https://www.computerhope.com/jargon/e/event-listener.htm#:~:text=An%20event%20listener%20is%20a,for%20an%20event%20to%20occur.&text=The%20listener%20is%20programmed%20to,specific%20to%20Java%20and%20JavaScript.)

- **Event Handler** - An event handler is a routine that deals with the event, allowing a programmer to write code that is executed when the event occurs. [Resource](https://www.computerhope.com/jargon/e/event.htm)

- **Event Driven Programming** - Simply put, event-driven programming is when a program is designed to respond to user engagement in various forms. It is known as a programming paradigm in which the flow of program execution is determined by “events.” [Resource](https://www.edgetechacademy.edu/node-js/event-driven-programming/)

- **Event Loop** - The event loop is what allows Node.js to perform non-blocking I/O operations — despite the fact that JavaScript is single-threaded — by offloading operations to the system kernel whenever possible. [Resource](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)

- **Event Queue** - An event queue is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system. [Resource](https://www.techopedia.com/definition/24963/event-queue)

- **Call Stack** - A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc. [Resource](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)

- **Emit/Raise/Trigger** - Triggers events that cause function objects to be called [Resource](https://stackabuse.com/handling-events-in-node-js-with-evenemitter/)

- **Subscribe** - Listens for events to be emitted and acts accordingly [Resource](https://stackabuse.com/handling-events-in-node-js-with-evenemitter/)

- **database** - An organized collection of structured information or data stored in a computer.

## Preview

1. Which 3 things had you heard about previously and now have better clarity on? OSI Model, TCP Handshakes, Web Sockets

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Socket.io

3. What are you most excited about trying to implement or see how it works? Implementing socket applications


