# 🚀 Dockerized Node.js App

This is a simple Node.js application containerized with Docker. It can be used for learning Docker, Jenkins automation, or CI/CD basics.

---

## 📦 Project Structure
local-devops-app/
├── Dockerfile
├── package.json
├── package-lock.json
├── server.js
└── public/
    └── index.html

## 🐳 Docker Commands

### Build the Docker image:
docker build -t local-devops-app .

### Run the Docker Container:
docker run -d -p 8080:80 local-devops-app

###To find all running Docker containers, use this command:
docker ps

###If you only want the container IDs:
docker ps -q

###To Stop a Container:
docker stop <container id>

### To run app : go to : http://localhost:8080






