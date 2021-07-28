# Chat-Application-using-Socket-programming
Introduction

JAVA socket programming is popular when it comes to projects involving networks. Our project primarily consists of a server and multiple clients and the focus is laid on the communication between these clients and understanding the role of the network in this process. With the help of sockets, connections are established among the clients and the server and there's been a great use of other functions within socket programming. As our project involves creating multiple clients, it was achieved with the help of the Multithreading concept in JAVA. The goal is to develop a chat application that handles multiple clients simultaneously and to test the performance of the network while handling a large number of clients.

Architecture

The architecture of our model consists of a single server and multiple clients. Each client is connected to the server through a socket. A new thread is used when a new client is connected to the server. Hashmap is being used to store the clients. The clients chat box is given a Graphical User Interface that contains a Textfield where the message to be sent is entered and it also consists of a text area where the received messages are displayed.

Working 

Initially, the server is started and it's ready to accept new clients. Each client is then called and is connected and a communication link is established between various clients with the help of Usernames where each username of a client is unique. So to send a message to a particular client, we need to name the client in the text field like " @clientname: ". By using this in the chatbox, we can send a message to a unique client.

How to run:
Compile: Go to the home directory and type "make".
Run: Java ChatServer and Java ChatClient.

![Time delay in messages](https://user-images.githubusercontent.com/33234287/127380219-a937379d-11fa-4508-bdc3-2a955999359d.png)
