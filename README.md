# Containerized Full-Stack Application with Docker & Docker Compose
This repository provides a containerization layer for full-stack applications. It is designed to orchestrate a Node.js frontend and backend using Docker and Docker Compose.

## 🏗️ Project Structure
The repository is organized to separate the infrastructure logic from the application source code:

```text
├── backend/            # Dedicated environment for the Backend API
├── myChatbot/          # Dedicated environment for the Frontend (Chatbot UI)
├── docker-compose.yml  # Orchestration script managing networks, ports, & env variables
└── README.md           # Project documentation
```

### How to Use
Follow these steps to get your full-stack application up and running locally:

Place your frontend files in the ```/myChatbot ``` folder.

Place your backend files in the ``` /backend ``` folder.

### Configure API Keys:

```export OPENROUTER_API_KEY=your_key_here```

### Run with Docker Compose:

```docker-compose up --build```

### Once the build completes and the services are healthy, you can access the application layers via your browser:

Frontend: http://localhost:3000

Backend: http://localhost:5000
