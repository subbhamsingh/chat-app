# Chat App

A real-time chat application built using Node.js, Express, React, Redux, DaisyUI, and Socket.IO. This project allows users to send and receive messages in real-time, with support for both private and group chats.

## Features

- **Real-Time Messaging**: Users can send and receive messages instantly with real-time communication using Socket.IO.
- **User Authentication**: Sign up, log in, and manage user sessions securely.
- **Private and Group Chats**: Users can chat with individuals or participate in group conversations.
- **Message History**: The app stores the history of messages for users to view previous conversations.
- **Responsive UI**: A simple, clean, and responsive user interface built with [DaisyUI](https://daisyui.com/) and [Tailwind CSS](https://tailwindcss.com/).
- **State Management**: Uses [Redux](https://redux.js.org/) for managing app state across the components.

## Tech Stack

- **Frontend**:
  - [React](https://reactjs.org/) for building the user interface.
  - [Redux](https://redux.js.org/) for state management.
  - [DaisyUI](https://daisyui.com/) (built on top of Tailwind CSS) for responsive UI components.
  - [Socket.IO-client](https://socket.io/docs/v4/client-api/) for real-time communication on the frontend.
  - [Tailwind CSS](https://tailwindcss.com/) for styling.

- **Backend**:
  - [Node.js](https://nodejs.org/) as the server-side runtime.
  - [Express](https://expressjs.com/) for building RESTful APIs.
  - [Socket.IO](https://socket.io/) for real-time communication on the backend.
  - [MongoDB](https://www.mongodb.com/) as the database for storing user data and chat history.

- **Authentication**:
  - [JWT](https://jwt.io/) for secure authentication and session management.

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:

   git clone https://github.com/subbhamsingh/chat-app.git


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/subbhamsingh/chat-app.git


Navigate to the project directory:
cd chat-app


Install the dependencies for both frontend and backend:

npm install

Set up environment variables:

Create a .env file and configure necessary values like MongoDB URI, JWT secrets, etc.

Run the project:

npm start

Usage
Open the app in your browser.
Create a new account or log in to start chatting.
