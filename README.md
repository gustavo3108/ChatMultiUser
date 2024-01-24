ChatMultiUser Java Project
Overview
This Java project implements a simple Multi-User Chat application with a client-server architecture. The application comprises three main classes: Client, ClientHandler, and Server. The project allows multiple clients to connect to a central server and engage in real-time chat communication.

Classes
Client: The Client class represents an individual user's client application. It facilitates the connection to the server and handles user input and output.

ClientHandler: The ClientHandler class is responsible for managing each client's communication on the server-side. It handles incoming messages from clients and broadcasts them to all connected clients.

Server: The Server class acts as the central hub for communication. It accepts incoming connections from clients, assigns a ClientHandler to each connected client, and manages the overall chat communication.

Features
Multi-User Chat: Connect multiple clients to the server simultaneously and engage in real-time chat.
Server-Client Interaction: Efficient communication between the server and individual clients using the ClientHandler class.
Scalability: Easily scalable for handling a growing number of connected users.
