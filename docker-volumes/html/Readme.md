# Docker Volumes – Data Persistence

## 📌 Overview
This example demonstrates how Docker volumes persist data even when containers are restarted or removed.

## 🧠 Key Concept
Containers are ephemeral. Volumes allow data to live outside the container lifecycle.

## ▶ Run Command
```bash
docker run -d -p 8081:80 \
-v ${PWD}/html:/usr/share/nginx/html \
--name nginx-volume nginx:alpine

---
