# Deployments: Production Applications

## Overview

Production-ready applications, containerization, and deployment configurations.

---

## Folders

### 1. Streamlit Apps
Interactive data science dashboards
- Model demos
- Data explorers
- Analytics dashboards

### 2. FastAPI Services
REST APIs for ML models
- Prediction endpoints
- Model serving
- Real-time inference

### 3. Docker & Containerization
Container configs for deployment
- Dockerfile templates
- Docker Compose
- CI/CD pipelines

### 4. Kubernetes
Orchestration & scaling
- K8s manifests
- Helm charts
- Pod configurations

---

## Quick Deploy

```bash
# Streamlit
streamlit run app.py

# FastAPI
uvicorn main:app --reload

# Docker
docker build -t ml-app .
docker run -p 8000:8000 ml-app

# Kubernetes
kubectl apply -f k8s/
```

**See individual folders for detailed instructions.**