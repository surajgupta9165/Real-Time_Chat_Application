Real-Time Chat Application

Overview

This is a real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack with Socket.io for real-time communication.

Features

User authentication (Signup/Login)

Real-time messaging using Socket.io

Private and group chat functionality

Responsive UI with TailwindCSS and DaisyUI

Emoji support

Tech Stack

Backend

Node.js

Express.js

MongoDB (Mongoose)

JWT Authentication

Socket.io

Frontend

React.js

Redux Toolkit for state management

TailwindCSS with DaisyUI

React Router for navigation

Axios for API requests

Socket.io-client for real-time messaging

Installation and Setup

Prerequisites

Ensure you have the following installed:

Node.js (v14+)

MongoDB

Backend Setup

Clone the repository:

git clone https://github.com/your-repo/chat-app.git
cd chat-app/backend

Install dependencies:

npm install

Configure environment variables:

Create a .env file in the backend root directory.

Add the following variables (modify as needed):

PORT=4000
MONGODB_URI=your-mongodb-uri
JWT_SECRET_KEY=your-secret-key

Start the server:

npm start

Frontend Setup

Navigate to the frontend directory:

cd ../frontend

Install dependencies:

npm install

Start the frontend:

npm start

Open http://localhost:3000 in your browser.

Running the Application

Start the backend server (npm start in backend folder)

Start the frontend (npm start in frontend folder)

The application should now be running at http://localhost:3000

API Endpoints

POST /api/v1/user/register - User registration

POST /api/v1/user/login - User login

GET /api/v1/message - Fetch messages

POST /api/v1/message - Send message

WebSocket Events

connect - Establish socket connection

disconnect - Handle disconnection

sendMessage - Send a new message

receiveMessage - Receive a new message

Author

Developed by Suraj gupta
