# Docker Environment Variables

## 📌 Overview
Environment variables allow configuration without changing application code.

## ▶ Build Image
```bash
docker build -t docker-env-demo .



##run a acontainer 
docker run docker-env-demo


##overrise a variable
docker run -e APP_ENV=dev -e APP_VERSION=2.0 docker-env-demo
