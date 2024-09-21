# streamlit-kubernetes

# Streamlit with Kubernetes

This project demonstrates how to run a Streamlit app in a Kubernetes cluster using Docker.

## Setup Instructions

### Step 1: Dockerize the Streamlit App

- Build the Docker image:
  ```bash
  docker build -t streamlit-app:latest .

  docker tag streamlit-app:latest your-dockerhub-username/streamlit-app:latest
docker push your-dockerhub-username/streamlit-app:latest


kubectl apply -f streamlit-deployment.yaml


kubectl get svc streamlit-app-service


git add .
git commit -m "Initial commit for Streamlit Kubernetes project"



git push origin main



