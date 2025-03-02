# MULTITHREADED-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: SAHIL ARINGALE

INTERN ID: CODHC179

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

# Multi-threaded Chat Application Using Java Sockets

This project is a functional chat application that allows multiple clients to communicate with a server in real-time. Built using Java sockets and multithreading, the application supports simultaneous connections from multiple users, enabling them to send and receive messages in a shared chat environment.

### Features:
- **Server and Client Communication**: The server listens for incoming client connections on a specified port. Once connected, clients can send and receive messages in real time.
- **Multithreading**: Each client is handled by a separate thread, allowing multiple clients to interact with the server simultaneously without blocking each other. This ensures that each client can send and receive messages independently.
- **Real-time Chat**: Clients can send messages to all connected clients, making it a group chat environment. The server forwards messages to all active clients.
- **User Interface**: Clients have a simple text-based interface where they can enter messages and view incoming messages from other clients.

### How It Works:
1. **Server**: The server listens for client connections on a specified port. Upon connection, it creates a new thread for each client to handle communication with that client individually.
2. **Clients**: Clients connect to the server using the server’s IP address and port number. They can send messages to the server, which then broadcasts the message to all other connected clients.
3. **Multithreading**: Each client is managed by its own thread on the server, ensuring that one client's message does not block others from sending or receiving messages.
4. **Real-time Communication**: Once connected, clients can send messages in real-time, and these messages are broadcast to all other connected clients via the server.

### Instructions:
1. **Clone the Repository**:
   ```
   git clone https://github.com/your-username/chat-application.git
   ```
2. **Run the Server**:
   - Compile and run the server using the following commands:
     ```
     javac Server.java
     java Server
     ```
3. **Run the Clients**:
   - Compile and run the client(s) using the following commands:
     ```
     javac Client.java
     java Client
     ```
   - Clients must enter the server's IP address and port number to connect.

### Example Output:
Clients will be able to see messages from other clients in the chat window, for example:
```
Client 1: Hello, everyone!
Client 2: Hi there! How are you?
Client 1: I'm doing great, thanks!
```

#OUTPUT: 
