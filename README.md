# AWS ECS CI/CD Pipeline Project

This project demonstrates an automated CI/CD pipeline for deploying a Dockerized web application to AWS ECS using CodePipeline and CodeBuild.

## Architecture

GitHub → CodePipeline → CodeBuild → Docker Image → Amazon ECR → ECS Fargate → Application Load Balancer

## Tools Used

- GitHub
- AWS ECS
- AWS ECR
- AWS CodePipeline
- AWS CodeBuild
- Docker
- Nginx

## Pipeline Workflow

1. Developer pushes code to GitHub
2. CodePipeline triggers build
3. CodeBuild builds Docker image
4. Image pushed to Amazon ECR
5. ECS service updates automatically
6. Application deployed behind ALB

## Features

- Automated CI/CD deployment
- Docker containerization
- AWS managed infrastructure
- Scalable ECS Fargate deployment
