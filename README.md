Full-Stack Node.js Docker Infrastructure
This repository provides a containerization layer for full-stack applications. It is designed to orchestrate a Node.js frontend and backend using Docker and Docker Compose.

🏗️ Project Structure
The repository is organized to separate the infrastructure logic from the application source code:

./myChatbot/ - Dedicated environment for the Frontend.

./backend/ - Dedicated environment for the Backend API .

docker-compose.yml - Orchestration script to manage networking, ports, and environment variables.

How to Use

Place your frontend files in the /myChatbot folder.

Place your backend files in the /backend folder.

Configure API Keys:

```export OPENROUTER_API_KEY=your_key_here```

Run with Docker Compose:

```docker-compose up --build```

Frontend: http://localhost:3000

Backend: http://localhost:5000
