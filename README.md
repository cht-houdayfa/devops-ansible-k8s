# DevOps CI/CD Project – Jenkins · Ansible · Docker · Kubernetes

## Overview
This project demonstrates a complete CI/CD pipeline where Jenkins pulls code from GitHub,
executes Ansible playbooks, deploys Docker containers, and updates application content automatically.

## Architecture
GitHub → Jenkins Pipeline → Ansible → Docker / Kubernetes → Web Application

## Stack
- Jenkins
- Ansible
- Docker
- Kubernetes (Minikube)
- Linux
- GitHub

## Pipeline Flow
1. Code is pushed to GitHub
2. Jenkins pipeline is triggered
3. Jenkins runs Ansible playbooks
4. Ansible deploys/recreates Docker containers
5. Application content is updated automatically

## How to Run
- Push changes to the repository
- Trigger Jenkins pipeline
- Access the application via:
  http://<server-ip>:8090

## Result
The webpage displays a custom message deployed automatically by Jenkins & Ansible.

## Author
Houdayfa Chtioui
``
