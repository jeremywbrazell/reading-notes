# Socket.io

1. **What is the benefit of transforming data into packets?**
it enables new innovations, services, and business opportunitiesand is also the most cost-effective, efficient, and scalable networks for content delivery.
[Ref](https://fntsoftware.com/blog/network-transformation-transitioning-to-packet-technology/)

1. **UDP is often refereed to as a connectionless protocol. Why is this?**
because No connection needs to be established between the source and destination before you transmit data.
[Ref](https://www.sciencedirect.com/topics/computer-science/connectionless-protocol#:~:text=UDP%20is%20a%20connectionless%20protocol,the%20payload%20is%20not%20corrupted.)

1. **Can a socket server application have multiple socket connections?**
Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.
[Ref](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port#:~:text=5%20Answers&text=A%20server%20socket%20listens%20on%20a%20single%20port.&text=Multiple%20connections%20on%20the%20same,system%20resources%20allow%20it%20to.)

1. **Can a socket connection application be connected to multiple socket servers?**
Yes.  There are 2 things to consider when doing so:
- enabling sticky session, if HTTP long-polling is enabled (which is the default)
- using a compatible adapter
[Ref](https://socket.io/docs/v4/using-multiple-nodes/)

1. **Can an application be both a socket server and a socket connection?**
Yes.  Each socket.io instance needs to be on a different path (one can be the default path and one can be custom), which means that you need to set the path option in both socket.io client and socket.io server to match for one of the servers.
[Ref](https://stackoverflow.com/questions/60029843/multiple-socket-io-servers-sharing-a-single-http-s-server)

# Vocab Terms

1. **Observer Pattern**
software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
[Ref](https://en.wikipedia.org/wiki/Observer_pattern)

1. **Listener**
a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.
[Ref](https://www.geeksforgeeks.org/javascript-addeventlistener-with-examples/)

1. **Event Handler**
scripts that are automatically executed when an event occurs
[Ref](http://home.ubalt.edu/abento/701/javascript/eventehand.html)
;
1. **Event Driven Programming**
JavaScript in the browser uses an event-driven programming model. Everything starts by following an event. The event could be the DOM is loaded, or an asynchronous request that finishes fetching, or a user clicking an element or scrolling the page, or the user types on the keyboard
[Ref](https://flaviocopes.com/javascript-events/)

1. **Event Loop**
main execution loop of every function that is invoked from any asynchronous event.  It is also what allows Node.js to perform non-blocking I/O operations — despite the fact that JavaScript is single-threaded — by offloading operations to the system kernel whenever possible.
[Ref](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)

1. **Event Queue**
queue that is responsible for sending new functions to the track for processing. It follows the queue data structure to maintain the correct sequence in which all operations should be sent for execution
[Ref](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)

1. **Call Stack**
stack that is responsible for keeping track of all the operations in line to be executed
[Ref](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)

1. **Emit/Raise/Trigger**
starting off of a process

1. **Subscribe**
Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures
[Ref](https://aws.amazon.com/pub-sub-messaging/)

1. **database**
an organized collection of data stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques
[Ref](https://en.wikipedia.org/wiki/Database)

# Additional Resources

## Videos
- [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
- [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

## Readings
- [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
- [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
- [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
- [Socket.io Documentation](https://socket.io/docs/v4/)
- [Socket.io Server API](https://socket.io/docs/v4/server-api)
- [Socket.io Client API](https://socket.io/docs/v4/client-api)
- [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)