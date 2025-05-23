## 🐳 Code Editor (Fullstack App) – Local Development with Docker Compose
This repository contains the `docker-compose.yml` and shared configuration for running the fullstack application — backend and frontend — using Docker and Docker Compose.
        
The frontend and backend live in **separate repositories**, and are included here as Git submodules or via manual cloning.

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
    ```bash
    git clone https://github.com/AbubakrRehman/code_editor_pern.git
    ```
     ```bash
    cd code_editor_pern
    ```
- Add the Backend and Frontend Code
    ```bash
    git clone https://github.com/AbubakrRehman/code_editor_backend.git backend
    ```
     ```bash
    git clone https://github.com/AbubakrRehman/code_editor_frontend.git frontend
    ```
- Update End of Line Sequence
  - select *wait-for-it.sh* in VS Code
  - change End of Line Sequence from CRLF to LF from botton right of VS Code 

- Running the Project
    ```bash
    docker compose up --build
    ```
- Closing the Project
    ```bash
    docker compose down -v
    ```