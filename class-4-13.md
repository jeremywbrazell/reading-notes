# Message Queues

1. What does it mean that web sockets are bidirectional? Why is this useful?
Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.
- Benefits:
1. Speed: Because of WebSocket design (inherently small payloads, persistent connection that doesn’t rely on the response-request overhead), messages can be sent and received in real-time. Further, memory use is configurable.
1. Stability: WebSocket has been tested heavily across multiple platforms and continually passes Python’s industry-standard stress test: Autobahn Testsuite.
1. Simplicity: WebSocket itself takes care of managing the connections, so developers can focus on functionality and what they’re actually passing in messages between the client and the server. [Ref](https://medium.com/@nerdplusdog/websocket-simultaneous-bi-directional-client-server-communication-e7948203054b)

1. Does socket.io use HTTP? Why?
Yes.  The client will try to establish a WebSocket connection if possible, and will fall back on HTTP long polling if not.
1. What happens when a client emits an event?
Server listening for message event parses data sent by the client and broadcasts a data event containing the text entered by the user. GOTO step 4 until the user leaves the page or closes their browser which emits a disconnect event.[Ref](http://sahatyalkabov.com/jsrecipes/#!/backend/socketio-basics)
1. What happens when a server emits an event?
Clients listening for the data event parse and render data sent from the server.
1. What happens if a client “misses” an event?
The server will try to reconnect after the delay.
1. How can we mitigate this?  Error handlers on the server side.

## Vocab
- **Socket:** one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to.
- **Web Socket:**bidirectional, full-duplex protocol that is used in the same scenario of client-server communication
- **Socket.io:**a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers.
- **Client:**a piece of computer hardware or software that accesses a service made available by a server as part of the client–server model of computer networks
- **Server:**a piece of computer hardware or software that provides functionality for other programs or devices, called "clients"
- **OSI Model:**a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology
- **TCP Model:**the set of communications protocols used in the Internet and similar computer networks
- **TCP:** one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol 
- **UDP:**one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network. Prior communications are not required in order to set up communication channels or data path
- **Packets:**a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data; the latter is also known as the payload.

## Preview
1. Which 3 things had you heard about previously and now have better clarity on?
I now know the differences between TCP & UDP.  I also know the benefits of both.
1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Message Queues and how they tie into events and socket.io.
1. What are you most excited about trying to implement or see how it works?
see above.

## Reference Links
- [Socket.io Chat Example](https://socket.io/get-started/chat/)
- [Rooms](https://socket.io/docs/v4/rooms/)
-  [Namespaces](https://socket.io/docs/v3/namespaces/)
- [Socket.io Emit Cheatsheet](https://socket.io/docs/v3/emit-cheatsheet/)
