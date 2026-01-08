Hackaton - Network Blackjack

This project is a simple multiplayer Blackjack game built using a client–server architecture. It was created as part of a hackathon to demonstrate basic networking concepts and protocol design.
The server broadcasts its availability using UDP, allowing clients to automatically discover it without manual configuration. Once a client selects a server, the game communication is handled over a TCP connection.
Players compete against a dealer according to standard Blackjack rules. During the game, players can choose to hit or stand, and the server manages the game logic and determines the outcome of each round.
Both the client and the server use a shared binary protocol to ensure consistent and reliable communication. The server supports multiple clients simultaneously using multithreading.
The project focuses on simplicity, clarity, and demonstrating core ideas in network programming, including UDP discovery, TCP communication, and client–server design.
