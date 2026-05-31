# EduFriend – Full-Stack Learning Platform

## Overview

EduFriend is a cloud-based learning platform designed to help students access study materials, take quizzes, track academic performance, and monitor learning progress through a centralized dashboard.

The platform combines a React frontend with Flask REST APIs and Firebase services to provide a secure and scalable learning experience.

---

## Problem Statement

Students often use multiple tools for learning resources, quizzes, and performance tracking, creating a fragmented learning experience.

EduFriend addresses this challenge by providing:

* Centralized study materials
* Interactive quizzes
* Performance analytics
* Secure authentication
* Cloud-hosted accessibility

---

## System Architecture

```text
React Frontend
      │
      ▼
 Flask REST APIs
      │
      ▼
 Firebase Authentication
      │
      ▼
 Firestore Database
      │
      ▼
 Google Cloud Run Deployment
```

---

## Key Features

### User Authentication

* Firebase Authentication
* Secure login and session management
* Protected routes

### Learning Dashboard

* Student dashboard
* Study material management
* Progress tracking

### Quiz System

* Interactive quizzes
* Score tracking
* Performance evaluation

### Analytics

* Academic progress monitoring
* Learning insights
* Performance visualization

### Cloud Deployment

* Backend containerized using Docker
* Deployed on Google Cloud Run
* Frontend hosted using Firebase Hosting

---

## Tech Stack

### Frontend

* React
* JavaScript
* Axios
* CSS

### Backend

* Flask
* Python
* REST APIs

### Database & Authentication

* Firebase Authentication
* Firestore Database

### Cloud & DevOps

* Docker
* Google Cloud Run
* Firebase Hosting

---

## Repository Structure

```text
EduFriend/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── Dockerfile
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│
├── firebase.json
├── README.md
```

---

## Live Demo

Frontend:
https://edufriend-web-app.web.app/login

---

## Engineering Highlights

* Designed full-stack architecture using React and Flask
* Built RESTful APIs for learning workflows
* Implemented secure authentication using Firebase
* Containerized backend services using Docker
* Deployed cloud-native backend on Google Cloud Run
* Integrated Firestore for real-time data storage

---

## Future Improvements

* Role-based access control (RBAC)
* AI-powered learning recommendations
* Personalized study plans
* Advanced analytics dashboard
* Microservices architecture
* CI/CD automation

---

## Author

Aryanmouli Cherupalli

Software Engineer | Java | Spring Boot | React | Cloud | AI Applications
