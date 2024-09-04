# CI-Project

![image](https://github.com/user-attachments/assets/af086735-494b-4fe4-ac47-b1ccfbeee20d)

# Pre-requisite

- AWS Account
- Visual Studio Code
- GitHub Account
- DockerHub Account
- Application Source code repo: https://github.com/neelKarnavt/demo-counter-app.git

# TOOLS

1. AWS - Security Group, EC2
2. Source Code Management:Git
3. CI/CD : Jenkins
4. Build Tool : Maven
5. Code quality check: SonarQube
6. Artifact repository : Nexus and DockerHub
7. Containerization : Docker


# STAGES

Git Checkout
Unit Test
Intgration Test
Maven Build
Static Code Analysis
Quality Gates
Upload file to Nexus
Docker image build
Push image to docker hub

# ACCESS ALL THROUGH CONSOLE

1. Jenkins : http://<public_IP>:8080
2. SonarQube: http://<public_IP>:9000
3. Nexus: http://<Public_IP>:8081
