# JAVA CLIENT-SERVER CHAT APPLICATION

## Project Title

Java Socket Programming - Client Server Chat Application

## Project Description

This project demonstrates a simple Client-Server Chat Application developed using Java Socket Programming. It enables two-way communication between a server and a client running on the same computer (localhost).

The server waits for a client connection on port 2100. Once connected, both client and server can exchange text messages through the console until the client enters the keyword **"end"** to terminate the conversation.

---

## Files Included

1. chatserver.java

   * Creates the server.
   * Waits for client connection.
   * Receives messages from the client.
   * Sends replies back to the client.

2. chatclient.java

   * Connects to the server running on localhost.
   * Sends messages entered by the user.
   * Receives replies from the server.

---

## Technologies Used

* Java
* Java Socket Programming
* TCP/IP Communication
* BufferedReader
* PrintStream

---

## Requirements

* JDK 8 or above
* Command Prompt / Terminal
* Any Java IDE (Optional)

---

## Port Used

Port Number: 2100

---

## How to Compile

Open Command Prompt in the project directory.

Compile both files:

javac chatserver.java

javac chatclient.java

---

## How to Run

### Step 1

Start the server first.

java chatserver

Output:

server application is running

server is waiting at port 2100

---

### Step 2

Open another Command Prompt.

Run the client.

java chatclient

Output:

client application is running

connection is successful with server

---

## Working

1. Server starts and waits for a connection.
2. Client connects to the server.
3. Client enters a message.
4. Server receives the message.
5. Server replies.
6. Client receives the reply.
7. Communication continues until the client types:

end

After entering "end", the client disconnects and the application terminates.

---

## Features

* Console-based chat application
* Client-server communication
* Uses TCP sockets
* Real-time message exchange
* Easy to understand Java networking example

---

## Project Flow

Server
↓
Wait for Connection
↓
Client Connects
↓
Message Sent
↓
Message Received
↓
Reply Sent
↓
Reply Received
↓
Repeat Until "end"

---

## Classes Used

java.net.ServerSocket

java.net.Socket

java.io.BufferedReader

java.io.InputStreamReader

java.io.PrintStream

---

## Sample Conversation

Client:

Hello Server

Server:

Hello Client

Client:

How are you?

Server:

I am fine.

Client:

end

Connection Closed.

---

## Future Improvements

* GUI using Java Swing or JavaFX
* Multiple client support
* Username authentication
* File sharing
* Encryption of messages
* Chat history storage
* Private messaging
* Online user list

---

## Learning Outcomes

After completing this project, students will understand:

* Java Socket Programming
* TCP Client-Server Architecture
* ServerSocket and Socket classes
* Input and Output Streams
* Two-way communication using Java
* Basic networking concepts

---

## Author

Project: Java Client Server Chat Application

Language: Java

Concept: Socket Programming
