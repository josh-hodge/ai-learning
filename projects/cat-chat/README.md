# Cat Chat 🐱

A purr-fectly fun chat application that demonstrates client-server communication using WebSocket, with a delightful cat theme!

## Features
- Real-time messaging with cat-themed messages
- Cute and playful UI with cat patterns
- WebSocket-based communication
- Multiple client support
- Automatic "meow" additions to messages
- Welcome message for new users

## Prerequisites
- Node.js (version 12 or higher)
- npm (comes with Node.js)

## Installation
1. From the repo root, install dependencies:
   ```bash
   npm install
   ```

## Running the Application
1. Start the server from this directory:
   ```bash
   npm start
   ```
2. Open your browser and navigate to `http://localhost:3000`
3. Open multiple browser windows to test the chat functionality
4. Start sending meow-ssages to other users!

## How it Works
- The server uses Express.js to serve static files and WebSocket for real-time communication
- The client connects to the server using WebSocket
- Messages are broadcasted to all connected clients with added "meow!"
- The UI is built with vanilla HTML, CSS, and JavaScript
- Features a playful cat-themed design with Comic Sans MS font

## Learning Points
- Setting up a Node.js server
- WebSocket communication
- Client-server architecture
- Real-time data handling
- Basic frontend development
- CSS styling and animations
- DOM manipulation
