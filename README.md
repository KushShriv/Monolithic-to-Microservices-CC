# Monolithic to Microservices Application Cloud Computing Project

This project aims to develop an e-commerce microservices application that can be deployed on the cloud using Docker, Kubernetes, Jenkins, and Git. This would be done by transforming a Monolithic E-commerce application into a microservices based application.

## Project Overview

The application consists of several microservices deployed as Docker containers on a Kubernetes cluster. Jenkins is used for continuous integration and deployment, while Git is used for version control.

## Microservices

The application includes the following microservices:

1. **User Management**: Handles user registration, authentication, and authorization.
2. **Product Management**: Handles product management, including adding, editing, and deleting products.
3. **Order Management**: Handles order management, including viewing order history, tracking orders, and managing orders.
4. **Review Management (optional)**: Handles product review management, allowing users to view and add reviews.

## Technologies Used

<div align='center'>
<img src = 'https://img.shields.io/badge/Next.js-000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white'>
<img src = 'https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white'>
<img src = 'https://img.shields.io/badge/Kubernetes-326CE5.svg?style=for-the-badge&logo=Kubernetes&logoColor=white'>
<img src = 'https://img.shields.io/badge/Jenkins-D24939.svg?style=for-the-badge&logo=Jenkins&logoColor=white'>
<img src = 'https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=Git&logoColor=white'>
</div>

- **Next.js**: For the Monolithic Application
- **Docker**: For containerization of microservices.
- **Kubernetes**: For orchestration and deployment of containers.
- **Jenkins**: For continuous integration and deployment.
- **Git**: For version control and code management.

## Getting Started

To get started with the project, follow these steps:

0. Build a Monolithic Web Application

1. Clone the repository:
```
git clone https://github.com/KushShriv/Monolithic-to-Microservices-CC.git
```

2. Build and run the Docker images for each microservice:
```
cd e-commerce-microservices/user-service
docker build -t user-service .
docker run -p 8080:8080 user-service
```
> Repeat this process for each microservice.

3. Set up Kubernetes and deploy the microservices using the provided manifests.

4. Configure Jenkins and set up the CI/CD pipeline for automated builds and deployments.