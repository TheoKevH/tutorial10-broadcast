# TUTORIAL 10 (BROADCAST)

**Name:** Theodore Kevin Himawan

**NPM:** 2306210973

**Class:** ADPRO A

## Reflection 2.1

### Server
![server](img/server.png)

### Client 1
![1](img/1.png)

### Client 2
![2](img/2.png)

### Client 3
![3](img/3.png)

>How to run it?

- Run the server: <code>cargo run --bin server</code>
- Run the clients: <code>cargo run --bin client</code>

>What happens when we type some text in the clients?

<p align="justify">When sending a text in the client, it will show up in the server (with the message and port names). Also, writing a text in any one of the client would result in the messaging being sent to all of the other active clients</p>