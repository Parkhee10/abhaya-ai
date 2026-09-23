# Abhaya AI — AI-Based Women Safety & Emergency Detection System

Android app that passively detects emergency-like phone motion using an
on-device ML classifier (accelerometer + gyroscope), confirms it isn't
accidental via a short cancellation window, then alerts trusted contacts
and shares live location through a Spring Boot backend.

## Status
🚧 In development — see `docs/` for the full synopsis and architecture.

## Tech Stack
- **Android**: Java/Kotlin, TensorFlow Lite (on-device inference)
- **Backend**: Java, Spring Boot, REST APIs
- **ML**: Python (scikit-learn/TensorFlow), exported to TFLite
- **Database**: MySQL / PostgreSQL
- **Notifications**: Firebase Cloud Messaging
- **Deployment**: Docker, Kubernetes

## Repo Structure
- `android-app/` — Android client
- `backend/` — Spring Boot microservices
- `ml-model/` — training scripts + exported models
- `docs/` — synopsis, architecture diagram, project plan

## Author
Parkhee Jha — BE-CSE, Chandigarh University
