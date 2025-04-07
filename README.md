# 🚀 Node.js CI/CD with GitHub Actions & Docker

A simple Node.js Express app with CI/CD using GitHub Actions and Docker.

## 🔧 Tech Stack
- Node.js + Express
- Docker
- GitHub Actions
- Docker Hub

## ⚙️ How It Works
1. Push to `main` triggers GitHub Actions.
2. Workflow builds Docker image.
3. Image is pushed to Docker Hub.

## 🐳 Local Development

```bash
docker build -t yourusername/nodejs-app .
docker run -p 3000:3000 yourusername/nodejs-app

