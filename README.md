# my-jenkins-cicd-first-project

Zomato Application - Jenkins CI/CD
📌 Project Overview
This project demonstrates a CI/CD workflow implemented using Jenkins, Docker, GitHub, and SonarQube.

The application source code is based on an existing open-source repository. My contribution to this project was focused on the DevOps implementation, including Jenkins pipeline configuration, Docker containerization, code-quality analysis, and application deployment.

🛠️ Technologies Used
Jenkins
Docker
Git
GitHub
SonarQube
Linux
Node.js
JavaScript
🔄 CI/CD Pipeline
GitHub
   ↓
Jenkins
   ↓
Checkout
   ↓
Install Dependencies
   ↓
Build
   ↓
SonarQube Analysis
   ↓
Docker Build
   ↓
Docker Container
   ↓
Application Deployment
🚀 My Contributions
Configured Jenkins for CI/CD automation
Created and configured a Jenkins pipeline
Connected the project with GitHub
Automated application build and deployment
Containerized the application using Docker
Configured Docker networking/port mapping
Integrated SonarQube for code-quality analysis
Troubleshot Jenkins and Docker issues
Verified the application after deployment
🐳 Docker
The application is containerized using Docker.

Example:

docker build -t zomato-app .
Run the container:

docker run -d -p 3000:3000 --name zomato zomato-app
Check running containers:

docker ps
🔧 Jenkins
The Jenkins pipeline automates the application deployment process.

The pipeline includes stages such as:

Checkout source code
Install dependencies
Build application
Run code-quality analysis
Build Docker image
Deploy Docker container
📸 Screenshots
Jenkins Pipeline
!Jenkins Pipeline

Docker Containers
!Docker Containers

Deployed Application
!Application

📚 Learning Outcomes
Through this project, I gained practical experience with:

CI/CD concepts
Jenkins Pipeline
Docker containerization
Git/GitHub integration
SonarQube
Linux commands
Application deployment
Troubleshooting CI/CD pipelines
🙏 Credit
The application source code was based on an existing repository. Full credit belongs to the original author for the application implementation.

This repository focuses on my DevOps, CI/CD, containerization, and deployment work.

⚠️ Disclaimer
This project is intended for educational and learning purposes.
