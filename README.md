# 🍃 Unwritten Legends – MongoDB

> Data Persistence for the Unwritten Legends microservice ecosystem

---

## 📦 Part of Unwritten Legends

This repository contains the **MongoDB infrastructure** for the Unwritten Legends system.

| Repository | Purpose |
|------------|---------|
| [Unwritten-Legends-Backend](https://github.com/Sternenwarte88/Unwritten-Legends-Backend) | Application Services (Auth, Player, Realm, Dashboard) |
| [Unwritten-Legends-Redis](https://github.com/Sternenwarte88/Unwritten-Legends-Redis) | Session/Token Storage |
| **Unwritten-Legends-Mongo** | Data Persistence ← You are here |

---

## 🎯 Purpose

- Primary data store for Player and Realm modules
- Document-based storage for flexible game data
- Runs on shared `ul_network` for service communication

---

## 🚀 Getting Started

```bash
docker-compose up
```

MongoDB will be available at `localhost:27017`.

---

## 🔧 Configuration

| Setting | Value |
|---------|-------|
| Port | 27017 |
| Network | ul_network |
| Volume | mongo_data (persistent) |

---

## ⚠️ Security Note

For local development only. In production, use environment variables or secrets management for credentials.

---

## 👤 Author

**Stephan** – [@Sternenwarte88](https://github.com/Sternenwarte88)
