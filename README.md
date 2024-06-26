# Microservices Based Video to Audio Converter

## Overview
This project is a microservices-based system designed to convert video files to audio files. The architecture leverages the power of Flask, Docker, Kubernetes, and RabbitMQ to ensure scalability, reliability, and efficient processing.

## Features
- **Microservices Architecture**: Developed a modular system where each service handles a specific task.
- **Flask**: Used Flask to build the individual services.
- **Docker**: Containerized the services for consistency across different environments.
- **Kubernetes**: Deployed the services on a Kubernetes cluster for easy scaling and management.
- **RabbitMQ**: Implemented message queues for reliable asynchronous communication between services.
- **API Gateway**: Used to handle incoming requests and route them to the appropriate services.

## Technologies Used
- **Flask**: For developing the microservices.
- **Docker**: For containerizing the services.
- **Kubernetes**: For orchestrating the containers.
- **RabbitMQ**: For messaging and asynchronous communication.
- **Python**: Primary programming language used.
