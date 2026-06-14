# cloudops-ai


OVERVIEW
cloudops ai is a troubleshooting agent that helps users/organisations diagnose using AI integration and developed ML MODEL and resolve common cloud infrastructure issues.
application provides troubleshooting recommendations from user-reported cloud problems and serves as a learning project for cloud computing,backend development,frontend development,Machine learning.

Features (MVP)
1.Submit cloud-related issues
2.Receive troubleshooting recommendations
3.Store previous queries
4.View query history through a dashboard


Tech Stack:

Frontend
React

Backend
FastAPI
Python

Database
PostgreSQL

Version Control
Git
GitHub


Project Structure
cloudops-ai/
│
├── backend/
├── frontend/
├── docs/
└── README.md


Getting Started
Backend Setup
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

pip install fastapi uvicorn

uvicorn main:app --reload


Frontend Setup
cd frontend

npm install

npm start


Team Members
Backend Development
Frontend Development
Database Design
Documentation
DevOps & Deployment

Project Status

Phase 1 – Project Setup and MVP Development

Future Enhancements
AI-powered troubleshooting
Retrieval-Augmented Generation (RAG)
OCI integration
AWS integration
Real-time cloud monitoring


License

This project is developed for educational and learning purposes.
