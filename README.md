# Python-Data-Base
<small>Built by Brandon Yee</small>

Miniature Redis Build with Python using tutorial: ["Write your own miniature Redis with Python"](https://charlesleifer.com/blog/building-a-simple-redis-server-with-python/). This is my first project using Gevent in Python. 
This project is a simple Redis-like database server written in Python. The server is designed to be easy to understand and implement, and it supports basic data types like strings, numbers, dictionaries, and arrays.

# Goals

- Create a simple server that mimics Redis functionality.
- Use the server with a task queue project called Huey.

# Features

- Supports commands like GET, SET, DELETE, MGET, and MSET.
- Handles data types like strings, binary data, numbers, null, arrays, and dictionaries.
- Uses gevent for asynchronous handling of multiple clients.

# Implementation

- The server uses separate classes for handling protocols, server logic, and client interactions.
- The Redis protocol is used for communication between client and server. This protocol defines how data is encoded and sent over the network.
- The server stores data in a simple key-value store implemented as a Python dictionary.

# Benefits of this approach:

- Easy to understand and implement.
- Good starting point for learning about server development, sockets, and data structures in Python.
- Reusable protocol handling code for building a client library.

# Limitations 

- This is a simplified version for demonstration purposes only.
- It lacks features of a robust database server like persistence, security, and advanced error handling.
