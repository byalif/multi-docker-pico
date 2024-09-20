# Multi-Docker Pico 📸

A scalable, multi-container photo-sharing platform similar to Instagram, where users can register, share posts, and create profiles. Built using Docker and a microservices architecture.

## 🛠 Tech Stack

- **Frontend**: React, Redux, Docker
- **Backend**: Node.js, Express, MongoDB
- **Services**: NGINX, Redis, Travis CI for continuous integration
- **Containers**: Docker Compose for multi-container orchestration

## 🚀 Features

- User Authentication
- Photo Upload & Sharing
- Profile Creation & Management
- Realtime Updates with WebSockets

## ⚙️ Setup

```bash
git clone https://github.com/byalif/multi-docker-pico.git
cd multi-docker-pico
docker-compose up --build
