# Three-Tier Chat Application — Kubernetes Deployment (Minikube)

Deploying a real-time chat application (React frontend, Node.js/Express + Socket.io backend, MongoDB) onto Kubernetes using Minikube — manifests written and debugged by hand while learning Kubernetes through video tutorials.

## What I built

- **Kubernetes manifests** for all three tiers — frontend, backend, and database — written from scratch based on what I learned, not copy-pasted
- **Namespace-scoped deployment** to keep the app isolated
- **Service configuration** connecting frontend → backend → MongoDB inside the cluster
- **Deployed and tested on Minikube** end-to-end, verifying pod-to-pod communication

## What I debugged along the way

- YAML indentation and field pluralization errors
- Service/Deployment misconfigurations breaking pod networking
- Environment variable and secret handling for MongoDB connection strings

## Base application

The chat application itself (frontend/backend code) is adapted from an existing open-source real-time chat app — this repo focuses on the **Kubernetes/DevOps layer**: containerizing and orchestrating it, not the app's business logic.

## Stack

- **App:** React, Node.js/Express, Socket.io, MongoDB
- **Orchestration:** Kubernetes (Minikube)
- **Containerization:** Docker

---

**Author:** Vansh Khanna
**Connect:** [GitHub](https://github.com/Vanshkhanna123)
