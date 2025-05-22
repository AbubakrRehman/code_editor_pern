## 🐳 Code Editor (Fullstack App) – Local Development with Docker Compose
This repository contains the `docker-compose.yml` and shared configuration for running the fullstack application — backend and frontend — using Docker and Docker Compose.
        
The frontend and backend live in **separate repositories**, and are included here as Git submodules or via manual cloning.
    ----

## 📁 Project Structure
    project-root/
    ├── docker-compose.yml
    ├── .env # Shared environment variables (optional)
    ├── backend/ # Cloned or linked backend repo
    ├── frontend/ # Cloned or linked frontend repo
    └── README.md

## ✅ Prerequisites
  - Docker: https://www.docker.com/products/docker-desktop
  - Docker Compose: Included with Docker Desktop (v2.0+ recommended)
  - Git

## 🛠️ Project Setup
- Clone This Compose Repository
  - git https://github.com/AbubakrRehman/code_editor_pern.git
  - cd code_editor_pern
- Add the Backend and Frontend Code
  - git clone https://github.com/AbubakrRehman/code_editor_backend.git backend
  - git clone https://github.com/AbubakrRehman/code_editor_frontend.git frontend
- Running the Project
  - docker compose up --build

