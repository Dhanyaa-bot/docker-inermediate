
---

# 🔹 3️⃣ DOCKER NETWORKING (BASICS)

## 📄 `networking/README.md`
```md
# Docker Networking Basics

## 📌 Overview
Docker networking enables containers to communicate securely.

## ▶ Create Network
```bash
docker network create dev-network 

## Run Containers
docker run -d --name web1 --network dev-network nginx:alpine
docker run -d --name web2 --network dev-network nginx:alpine

##Inspect Network
docker network inspect dev-network