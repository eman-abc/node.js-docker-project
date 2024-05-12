# Docker Lab: Containerizing a Node.js Application

## Introduction
Hey there! Welcome to my Docker lab project where I'll be diving into the world of containerization with Docker. In this lab, I'll be containerizing a Node.js application to get hands-on experience with Docker and learn how to manage applications in a containerized environment.

## Objective
The main goal of this lab is to gain practical knowledge of Docker and understand its concepts by containerizing a Node.js application. By the end of this project, I hope to be comfortable creating Docker images, running containers, and managing Dockerized applications.

## Contents
- **Dockerfile:** This file contains instructions for building the Docker image for our Node.js application.
- **package.json:** Here, we define the metadata and dependencies for our Node.js application.
- **README.md:** You're reading it! This file provides detailed information about the lab exercise and what's included in this repository.

## Lab Tasks
### Task 1: Getting Started with Docker
1. **Pulling the Nginx Image:** I started by pulling the Nginx image from the Docker registry using the command `docker pull nginx`.

2. **Creating a Container from the Nginx Image:** Next, I created a container from the Nginx image using the command `docker run nginx`.

3. **Understanding Container Creation Output:** I carefully analyzed the output of creating the container to understand the initialization process and any messages displayed.

4. **Stopping the Container:** Using the command `docker stop <Container ID>`, I stopped the running container.

5. **Running Nginx Container on Port 3000:** To run the Nginx container on port 3000, I used the command `docker run -d -p 3000:80 nginx:latest`.

6. **Accessing Nginx Container via Web Browser:** I opened a web browser and navigated to `localhost:3000` to verify that the Nginx container was running and accessible.

### Task 2: Containerizing a Node.js Application
1. **Creating a Docker Image of our Node.js Application:** I developed a simple Node.js API or static website and created a Dockerfile with the necessary instructions to build the Docker image.

2. **Sharing GitHub Repository Link:** I uploaded the project files, including the Dockerfile, to a GitHub repository and shared the link as part of my lab submission.

## Usage
1. **Clone the Repository:** Clone this repository to your local machine.
2. **Navigate to the Repository Directory:** Use the `cd` command to navigate to the directory where you cloned the repository.
3. **Follow the Instructions:** Follow the instructions provided in the lab documentation to complete the tasks.

## Learning Resources
- [YouTube Tutorial 1](https://www.youtube.com/watch?v=pTFZFxd4hOI&t=305s)
- [YouTube Tutorial 2](https://www.youtube.com/watch?v=fqMOX6JJhGo&t=152s)
- [YouTube Tutorial 3](https://www.youtube.com/watch?v=3c-iBn73dDE&t=3855s)

## Author
This lab exercise was performed by Eman as part of SDA lab 12 at NUST.

## License
---
