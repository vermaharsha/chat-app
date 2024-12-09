# Real-Time Chatting App

A simple and intuitive real-time chatting application built using **Node.js** and **Socket.io**. This application allows users to join chat rooms and communicate with others in real time.

---

## Features

- Real-time messaging using Socket.io.
- Multiple users can join the same chat room and exchange messages.
- Unique usernames for each participant.
- Responsive and user-friendly interface.
- Notifications for new users joining or leaving the chat room.

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js
- **WebSocket Framework:** Socket.io

---

## Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14+ recommended)
- npm (Node Package Manager)

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run the application:**
   ```bash
   node index.js
   ```
4. **Open your browser and navigate to:**
   ```bash
   http://localhost:3000
   ```

---
# How It Works
- Users connect to the app through a web interface.
- Socket.io establishes a WebSocket connection for real-time communication.
- Messages are broadcasted to all users in the same chat room.
- Events like "user joined" or "user left" are emitted to update all users.
