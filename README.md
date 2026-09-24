# L02 Web Application

A containerized web service built with Python, Nginx, and Docker Compose, featuring a hit-counter application.

---

## 📌 Project Overview

This project demonstrates the setup and deployment of a multi-container environment using Docker. It routes traffic through an Nginx reverse proxy to a Python application backend with live visitor/request counting.

---

## 🛠 Tech Stack

- **Backend:** Python (`main.py`)
- **Web Server / Reverse Proxy:** Nginx (`nginx_default.conf`)
- **Containerization:** Docker & Docker Compose
- **Static Assets:** HTML (`www/index.html`)

---

## 📁 Project Structure

```text
.
├── docker-compose.yml       # Multi-container orchestration
├── Dockerfile               # Python service image definition
├── main.py                  # Application logic & API routes
├── requirements.txt         # Python package dependencies
├── nginx_default.conf       # Nginx server configuration
├── www/
│   └── index.html           # Frontend entry page
├── .env.example             # Template for environment variables
└── README.md                # Project documentation