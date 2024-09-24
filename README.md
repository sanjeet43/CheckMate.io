# CheckMate.io: A Real-Time Multiplayer Chess Game

## Overview

This project is a real-time multiplayer chess game built with Node.js and socket.io, allowing players to play chess against each other in real-time. The game features a simple drag-and-drop interface for moving pieces on a chessboard.

## Features

- Real-time multiplayer gameplay
- Drag-and-drop functionality for moving pieces
- Two-player roles: white and black
- Spectator mode for additional users
- Validations for player moves
- Displays the current state of the board

## Technologies Used

- **Node.js**: Server-side JavaScript environment
- **Express.js**: Web application framework for Node.js
- **Socket.io**: Library for real-time web applications
- **Chess.js**: JavaScript chess library for handling game logic
- **EJS**: Template engine for rendering HTML views
- **JavaScript**: Frontend Logic

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd <project-directory>
   ```

3. Install the required packages:

   ```
   npm install
   ```

## Running the Application

1. Start the server:

   ```bash
   npm start
   ```

2. Open your browser and go to:

   ```
   http://localhost:3000
   ```

## How to Play

- Open the game in multiple browser windows or tabs.
- The first two users will be assigned the roles of white and black players.
- Additional users will join as spectators.
- Players can drag and drop pieces to make their moves.

## Future Improvements

- Add user authentication
- Enhance the UI with animations
- Implement game history and replay functionality
- Add AI for single-player mode
