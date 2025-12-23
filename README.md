# Dockerized Static Website using Nginx

## Project Overview
This project demonstrates a simple static website containerized using Docker and deployed with Nginx. 
It is a beginner-friendly Docker project suitable for DevOps learning and showcasing on a resume.

---

## Project Structure
docker-nginx-project/
├── index.html
├── Dockerfile
└── README.md

---

## Tools & Technologies
- Docker
- Dockerfile
- Nginx
- Git & GitHub
- AWS EC2 (optional for deployment)

---

## Steps to Run the Project

### 1. Clone the repository
git clone <your-repo-url>
cd docker-nginx-project

### 2. Build the Docker image
docker build -t my-nginx-app .

### 3. Run the container
docker run -d -p 80:80 my-nginx-app

### 4. Access the website
Local: http://localhost
AWS EC2: http://<EC2-PUBLIC-IP>
