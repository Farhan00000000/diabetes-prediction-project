# Diabetes Prediction Project 🩺

A complete project to predict diabetes using machine learning, FastAPI backend, and an interactive frontend (Streamlit).

---

# Project Overview

This project predicts whether a patient has diabetes based on the Pima Indians Diabetes Dataset.

## Features include:
-	Model training using scikit-learn
-	FastAPI backend with endpoints for predictions
-	Dockerized backend for easy deployment
-	Interactive frontend for users to enter their data and get predictions
-	Live API and frontend links for testing

---

# 🔗 Project Links


| Component         | GitHub Repo                                      | Live Link                          |
|----------------|--------------------------------------------------|-------------------------------|
| Backend (FastAPI + Model Training + Docker)     |[Diabetes-Prediction-API-Frontend](https://github.com/Farhan00000000/Diabetes-Prediction-API-Frontend.git)      | Streamlit frontend app: [https://diabetes-prediction-app-4smzcurnuqvwawcwbmnjhs.streamlit.app](https://diabetes-prediction-app-4smzcurnuqvwawcwbmnjhs.streamlit.app) |
| Frontend (Streamlit / Web App)        | [diabetes-prediction-app](https://github.com/Farhan00000000/diabetes-prediction-app.git)                  | Backend API: [Backend API: https://diabetes-prediction-api-frontend.onrender.com](https://diabetes-prediction-api-frontend.onrender.com)    |

---

# Backend Details
- FastAPI app: Handles prediction requests
- Model training code: Train and save the ML model
- Dockerfile: Containerized backend for deployment
## Quick Start:
```bash
git clone https://github.com/Farhan00000000/Diabetes-Prediction-API-Frontend.git
cd Diabetes-Prediction-API-Frontend
# Build Docker container (make sure Dockerfile is here)
docker build -t diabetes-backend .
# Run container
docker run -p 8000:8000 diabetes-backend
```
API Documentation: Open [http://localhost:8000/docs](http://localhost:8000/docs) after running locally.
- **Note: Docker must be installed and running.*

---

# Frontend Details
- Interactive frontend built with Streamlit
- Connects to backend API to fetch predictions
```bash
git clone https://github.com/Farhan00000000/diabetes-prediction-app.git
cd frontend
pip install -r requirements.txt
streamlit run frontend.py
```
Or access directly via [Live Frontend](https://diabetes-prediction-api-frontend.onrender.com)

---

## Dataset
- **Pima Indians Diabetes Dataset**
- Kaggle link: [Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

# Notes
- Make sure backend is running before using frontend
- Docker ensures backend runs in any environment
-	Frontend provides a simple, user-friendly interface for predictions
