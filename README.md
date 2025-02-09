# ChatApp

## Overview
ChatApp is a full-stack real-time chat application built with React (frontend) and Node.js with Express (backend). It supports real-time messaging and user authentication.

## Features
- User authentication (Login/Register)
- Real-time messaging using WebSockets
- User avatars and profile management
- Responsive UI for both mobile and desktop
- Backend API built with Express.js and MongoDB
- Docker support for deployment

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js, MongoDB
- **Real-time Communication**: WebSockets (Socket.io)
- **Authentication**: JWT
- **Deployment**: Docker, Docker-Compose

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js & npm
- MongoDB
- Docker (optional, for containerized deployment)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Omhabib1/ChatApp.git
   cd ChatApp
   ```

2. Install dependencies for the frontend and backend:
   ```sh
   cd public
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.example` in `server/` and rename it to `.env`
   - Update database connection details

4. Start the backend:
   ```sh
   cd server
   npm start
   ```

5. Start the frontend:
   ```sh
   cd ../public
   npm start
   ```

## Running with Docker
```sh
docker-compose up --build
```

