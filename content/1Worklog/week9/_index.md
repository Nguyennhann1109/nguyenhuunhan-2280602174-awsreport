---
title : "Week 9"
date : "`r Sys.Date()`"
weight : 9
chapter : false
pre : "<b>1.9</b>"
---

# Developing Realtime Communication Features

## Objectives

- Develop the core real-time communication features of the system.
- Implement user presence management.
- Synchronize realtime data across Backend Realtime instances using Redis Pub/Sub.

## Duration

**From June 12, 2026 to June 18, 2026**

## Activities

| Day | Activities | References |
|:---:|------------|------------|
| **Fri** | Develop the **Presence Service** to manage users' online/offline status.<br><br>Handle user connection and disconnection events. | Socket.IO Documentation<br>Redis Documentation |
| **Sat** | Implement **Redis Pub/Sub** for synchronizing data across multiple Backend Realtime instances.<br><br>Verify event publishing and subscription through Redis channels. | Redis Pub/Sub Documentation |
| **Mon** | Develop the **Chat Handler** to process and broadcast realtime chat messages.<br><br>Test message delivery between multiple connected users. | Socket.IO Documentation |
| **Tue** | Implement the **Cache Service** using Redis to store online user information and temporary realtime data.<br><br>Improve data access performance. | Redis Documentation |
| **Wed** | Perform integration testing for the implemented realtime features.<br><br>Evaluate synchronization and concurrent connection handling. | Personal notes |

## Achievements

After completing the ninth week, I achieved the following outcomes:

- Successfully implemented user online/offline presence management.
- Integrated Redis Pub/Sub for realtime synchronization across Backend Realtime instances.
- Completed the realtime chat message processing workflow.
- Improved application performance by utilizing Redis as a caching layer.
- Verified that the implemented realtime features operated reliably in the development environment.

