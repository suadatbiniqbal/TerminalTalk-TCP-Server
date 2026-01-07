TerminalTalk TCP Server

=================================

TerminalTalk TCP Server is a simple C++ based TCP chat server designed for real-time communication through the terminal. It allows multiple clients to connect simultaneously and exchange messages over a TCP connection.

=======================

Features

TCP server–client architecture


Supports multiple concurrent clients

Broadcasts messages to all connected clients

Username-based identification

Minimal and lightweight implementation

Uses standard C++ and POSIX sockets

Build

Clone the repository and compile using the provided Makefile:

git clone https://github.com/suadatbiniqbal/TerminalTalk-TCP-Server.git
cd TerminalTalk-TCP-Server
make

Usage

Start the server:

./server


In separate terminals, start clients:

./client

Each client will be prompted for a username and can then send messages to all connected users.

Requirements

Linux or Unix-based system

g++ (C++11 or newer)

make

Overview

The server listens on a TCP port, accepts incoming client connections, and handles message broadcasting using multithreading. The project is intended for learning networking, socket programming, and basic concurrent server design in C++.
