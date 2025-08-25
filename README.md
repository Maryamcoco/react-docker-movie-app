# 🌟 DevOps Portfolio Project

This repository is part of my **DevOps Portfolio**, where I showcase hands-on projects demonstrating my skills in:

- 🚀 **Cloud Platforms** (AWS, GCP, Azure)  
- 🐳 **Containerization & Orchestration** (Docker, Kubernetes)  
- ⚙️ **Infrastructure as Code** (Terraform, Ansible)  
- 🔄 **CI/CD Pipelines** (Jenkins, GitHub Actions)  
- 📊 **Monitoring & Observability** (Prometheus, Grafana, Datadog, New Relic)  
- 🖥️ **Scripting & Automation** (Python, Bash, Go)  

Each project highlights a **key DevOps skill** I’ve learned and applied.  
The goal is to build real-world, portfolio-ready projects that prove my ability to design, automate, and manage scalable systems.  

---

# React Docker Movie App 🎬

This is a **React (Vite) movie application** that I built and deployed inside a **Docker container**.  
The project demonstrates how frontend applications can be containerized and run in isolated environments — ensuring consistent builds and deployments across systems.  

---

## 📖 Project Overview
- Built with **React (Vite)** for fast and modern frontend development.  
- Created a **Dockerfile** to package and run the app inside a container.  
- Exposed the app on **port 5173** (default Vite development server).  
- Demonstrates how frontend apps can also benefit from **containerization** for portability and reproducibility.  

This project showcases my skills in **frontend containerization** as part of a modern DevOps workflow.  

---

## 🛠️ Tools & Technologies
- **React (Vite)**  
- **Node.js 20 (Bullseye)**  
- **Docker**  
- **npm**  

---

## ⚙️ How It Works
1. The `Dockerfile` sets up a Node.js runtime.  
2. `package.json` and dependencies are installed.  
3. The app source code is copied into the container.  
4. The Vite development server is started on port **5173**.  

---

## 🚀 Running the Project

### 1️⃣ Clone the repository
```
git clone https://github.com/your-username/react-docker-movie-app.git
```
```
cd react-docker-movie-app
```
### 2️⃣ Build the Docker image
```
docker build -t react-docker-movie-app.
```
### 3️⃣ Run the container
```
docker run -p 5173:5173 react-docker-movie-app
```
App runs on 👉 http://localhost:5173

### 📸 Demo Screenshot
Example running locally: 
[moviepulse screenshot](https://github.com/Maryamcoco/react-docker-movie-app/blob/main/Screenshot%202025-08-25%20172242.png)
---
### 🎯 What I Learned
- How to containerize a React (Vite) frontend application.

- How to expose and run frontend apps inside Docker containers.

- How frontend and backend apps can both be containerized for consistent environments.

- Reinforced understanding of port mapping in Docker (5173:5173).
---
### 🔮 Future Enhancements
- Add an external movie API (e.g., TMDb API) for real data.

- Configure a production-ready build and serve with Nginx.

- Deploy to a cloud provider (AWS/GCP/Azure).

- Integrate CI/CD pipelines for automated builds.
---
### 👨‍💻 About Me
I’m a Junior DevOps Engineer passionate about building scalable systems and cloud-native applications.
This project is part of my DevOps Portfolio, where I demonstrate my ability to apply real-world tools and concepts.
---
### 🔗 Connect with me:

_ [LinkedIn](https://www.linkedin.com/in/maryam-temitope-2a3428373/)

---
### 📸 Demo video
[Moviepulse video](https://github.com/Maryamcoco/react-docker-movie-app/blob/main/vite%20in%20browser%20video%20.mp4)
