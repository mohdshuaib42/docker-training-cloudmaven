# docker-training-cloudmaven

# Docker Networking Experiments

This repository documents various Docker networking modes with hands-on examples.

---

## 1. Default Bridge Network
When no network is specified, Docker uses the **default bridge network**.

```bash
# Run Nginx container
docker run -d --name nginx-container nginx

# Run Alpine container
docker run -it --name alpine-container alpine sh

# Inspect bridge network
docker network inspect bridge


# Docker: Bind Mount vs Named Volume (Hands-on Learning)

This project demonstrates the difference between **bind mounts** and **named volumes** in Docker using a simple Node.js app.

---

## 🟢 Prerequisites
- Docker installed
- Basic knowledge of Node.js & Docker commands

---

## 🟢 Step 1: Create a Node.js App
```bash
mkdir node-app
cd node-app
