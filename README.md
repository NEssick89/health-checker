# System Health Checker (DevOps Skill Project)

This is a lightweight Python application designed to gather basic system metrics including CPU usage, memory utilization, and disk space. The purpose of this project is to practice and demonstrate core DevOps skills through a complete delivery workflow.

## Features

- Collects system health metrics using Python and `psutil`
- Containerized using Docker for consistent runtime behavior
- Includes a CI/CD pipeline using GitHub Actions (to be added)
- Designed for eventual deployment on AWS (EC2)

## Purpose

This project is not meant to solve a production problem, but rather to showcase a complete DevOps workflow including:

- Writing and managing simple, testable code
- Building Docker images
- Creating CI/CD automation pipelines
- Preparing for cloud-based deployment

## Future Improvements

- Automatically logging metrics to a file
- JSON output formatting for integration
- Uploading logs to S3 or another cloud service

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/health-checker.git
cd health-checker

# Build the Docker image
docker build -t health-checker .

# Run the container
docker run health-checker
