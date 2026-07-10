---
title : "Week 8"
date : "`r Sys.Date()`"
weight : 8
chapter : false
pre : "<b>1.8</b>"
---

# Building the Backend Realtime Foundation

## Objectives

- Initialize the Backend Realtime service for the project.
- Build the foundation for real-time communication using Socket.IO.
- Configure the development environment, Redis, and JWT-based socket authentication.

## Duration

**From June 5, 2026 to June 11, 2026**

## Activities

| Day | Activities | References |
|:---:|------------|------------|
| **Fri** | Initialize the **Backend Realtime** project using Node.js and Express.<br><br>Install required dependencies including Socket.IO, Redis, PostgreSQL, and JWT. | Socket.IO Documentation<br>Express.js Documentation |
| **Sat** | Organize the project structure into Config, Services, Handlers, Sockets, and Middlewares.<br><br>Configure the development environment and environment variables. | Node.js Documentation |
| **Mon** | Configure PostgreSQL and Redis connections.<br><br>Initialize Redis clients for caching and inter-service synchronization. | Redis Documentation<br>PostgreSQL Documentation |
| **Tue** | Implement JWT authentication through Socket Middleware.<br><br>Validate users before establishing WebSocket connections. | JWT Documentation<br>Socket.IO Middleware |
| **Wed** | Implement the Socket Connection lifecycle, including client connection and disconnection events.<br><br>Verify the Backend Realtime service in the local development environment. | Socket.IO Documentation |

## Achievements

After completing the eighth week, I achieved the following outcomes:

- Successfully initialized the Backend Realtime project using Node.js and Express.
- Configured the development environment for the WebSocket service.
- Established PostgreSQL and Redis connections for the realtime backend.
- Implemented JWT-based authentication before allowing socket connections.
- Completed the foundational architecture for implementing realtime features in the following weeks.
