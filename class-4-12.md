# Socket.io

1. **What is the benefit of transforming data into packets?**

1. **UDP is often refereed to as a connectionless protocol. Why is this?**
because No connection needs to be established between the source and destination before you transmit data.
[Ref](https://www.sciencedirect.com/topics/computer-science/connectionless-protocol#:~:text=UDP%20is%20a%20connectionless%20protocol,the%20payload%20is%20not%20corrupted.)

1. **Can a socket server application have multiple socket connections?**
Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.
[Ref](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port#:~:text=5%20Answers&text=A%20server%20socket%20listens%20on%20a%20single%20port.&text=Multiple%20connections%20on%20the%20same,system%20resources%20allow%20it%20to.)

1. **Can a socket connection application be connected to multiple socket servers?**

1. **Can an application be both a socket server and a socket connection?**

# Vocab Terms

1. **Observer Pattern**

1. **Listener**

1. **Event Handler**

1. **Event Driven Programming**

1. **Event Loop**

1. **Event Queue**

1. **Call Stack**

1. **Emit/Raise/Trigger**

1. **Subscribe**

1. **database**