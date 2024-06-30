
## Simple Chat Application

### Overview

This project is a simple real-time chat application with a frontend built using React.js and a backend using Node.js with Express and Socket.IO. It leverages Docker and Docker Compose for containerization and ease of deployment. The application demonstrates the use of WebSockets for real-time communication, JWT for authentication, and a MongoDB database for persistent storage.

### Features

- **Real-time Messaging**: Instant message updates using WebSockets (Socket.IO).
- **User Authentication**: JWT-based authentication for secure access.
- **Persistent Storage**: MongoDB for storing user data and chat messages.
- **Containerized Services**: Dockerized frontend, backend, and database for easy deployment and scaling.
- **Reverse Proxy**: Nginx is used as a reverse proxy to manage requests to the frontend and backend services.

### Folder Structure

```
simple-chat-app/
│
├── backend/
│   ├── Dockerfile
│   ├── package.json
│   ├── yarn.lock
│   └── index.js
│
├── frontend/
│   ├── Dockerfile
│   ├── package.json
│   ├── yarn.lock
│   ├── public/
│   │   └── index.html
│   └── src/
│       ├── App.js
│       └── index.js
│
└── docker-compose.yml
```

### Installation and Usage

#### Prerequisites

- Docker
- Docker Compose

#### Steps to Run the Application

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/SiwantRoy/Docker-Proj2-Compose.git
   cd simple-chat-app
   ```

2. **Build and Start the Containers:**
   ```bash
   docker-compose up --build
   ```

3. **Access the Application:**
   - Frontend: `http://localhost:3000`
   - Backend: `http://localhost:5000`

### Usage

1. **Open the frontend in your browser at `http://localhost:3000`.**


### Technologies Used

- **Frontend:**
  - React.js
  - Docker

- **Backend:**
  - Node.js
  - Express
  - Socket.IO
  - MongoDB
  - JWT Authentication
  - Docker

- **Other:**
  - Nginx (Reverse Proxy)
  - Docker Compose




