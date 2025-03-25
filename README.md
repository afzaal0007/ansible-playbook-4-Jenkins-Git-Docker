## ansible-playbook-4-Jenkins-Git-Docker

# Ansible playbook that automates the setup of a complete CI/CD pipeline environment for a development project. This solution covers the installation of Jenkins, Docker, Git, and the configuration of GitHub integration for automating the build and deployment of applications, particularly focusing on a Java Spring Boot application.

Problem Scenario:
The problem we're solving is to automate the setup of a continuous integration and delivery pipeline on a new server. This pipeline will build, test, and deploy a Java Spring Boot application with Docker support.

Solution:
The playbook will:

Install Docker and start Docker service.
Install Jenkins and start the Jenkins service.
Install Git to clone repositories.
Install Java (for Spring Boot apps).
Configure Jenkins to pull code from GitHub, build the Spring Boot application, and containerize it using Docker.
