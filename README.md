# MEAN CRUD Application – DevOps Assignment

This repository contains the complete DevOps implementation for a full-stack **MEAN (MongoDB, Express, Angular, Node.js)** CRUD application.  
This assignment demonstrates my experience with **containerization, cloud deployment, CI/CD automation, and reverse proxy setup**.

---
## 📌 Project Overview
This project is a **containerized MEAN (MongoDB, Express, Angular, Node.js) application**, deployed on an **AWS EC2 Ubuntu server** using:

- Docker & Docker Compose  
- MongoDB (containerized)
- Nginx Reverse Proxy  
- GitHub Actions CI/CD  
- Docker Hub Image Registry  

## 📌 Assignment Requirements
As part of the DevOps task, I was required to:

- Containerize the **frontend (Angular)** and **backend (Node.js)**.
- Build and push Docker images to **Docker Hub**.
- Deploy the application on an **AWS EC2 Ubuntu server** using Docker Compose.
- Configure **MongoDB** (Docker container).
- Set up **NGINX reverse proxy** on port 80.
- Create a **CI/CD pipeline** using GitHub Actions that:
  - Builds images on every push
  - Pushes them to Docker Hub
  - SSH into EC2
  - Pulls latest images & restarts containers

---

## 🚀 What I Implemented
- ✔ Dockerfile for frontend & backend  
- ✔ Docker Compose for full stack (Frontend + Backend + MongoDB)  
- ✔ AWS EC2 deployment  
- ✔ NGINX reverse proxy → `http://<EC2-IP>`  
- ✔ GitHub Actions CI/CD pipeline (Docker build + push + auto deploy)  
- ✔ Connected backend to MongoDB inside container  
- ✔ Fixed environment variables using `process.env.MONGO_URL`

---

## 🛠 Tech Stack
- **Angular**  
- **Node.js / Express**  
- **MongoDB**  
- **Docker & Docker Compose**  
- **AWS EC2 (Ubuntu 22.04)**  
- **NGINX**  
- **GitHub Actions (CI/CD)**

---
** CI/CD – GitHub Actions

Automatically:

Builds Docker images

Pushes to Docker Hub

Connects to EC2

Pulls latest images

Restarts containers**

☁️ AWS Deployment (EC2)

Ubuntu 22.04 EC2 instance

Installed Docker & Docker Compose

Pulled images from Docker Hub




🙋‍♂️ Author
Ashwath Amudhan C A
Aspiring DevOps & Cloud Engineer
