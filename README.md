# 🎟️ Event Registration System

A full-stack **Event Registration System** built with **FastAPI (Python)** for the backend, **React.js** for the frontend, and **MySQL** for data storage.  
This app allows users to create, view, and register for events through a modern, responsive interface — fully containerized using Docker.

---

## 🚀 Features

✅ Create, update, and delete events  
✅ Register users for events  
✅ RESTful FastAPI backend  
✅ React + CSS responsive frontend  
✅ MySQL database with connection pooling  
✅ Dockerized setup (backend, frontend, DB)  
✅ Ready for free cloud deployment  

---

## 🧱 Project Structure

📦 event-registration-system/
├── backend/
│ ├── main.py
│ ├── database.py
│ ├── routes/
│ │ ├── events.py
│ │ └── registrations.py
│ ├── requirements.txt
│ └── Dockerfile
│
├── frontend/
│ ├── src/
│ ├── public/
│ ├── package.json
│ └── Dockerfile
│
├── docker-compose.yml
└── README.md


---

## 🛠️ Tech Stack

| Layer | Technology |
|:------|:------------|
| **Frontend** | React.js, CSS3, JavaScript |
| **Backend** | FastAPI (Python 3.11) |
| **Database** | MySQL 8.0 |
| **Containerization** | Docker & Docker Compose |
| **Deployment Options** | DigitalOcean, Render, or Railway |

---

## ⚙️ Local Setup (Using Docker)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/event-registration-system.git
cd event-registration-system
2️⃣ Build and Start Containers
docker-compose up --build


This will start:

MySQL → port 3307

Backend (FastAPI) → port 8000

Frontend (React) → port 80

3️⃣ Access the App

Frontend → http://localhost

Backend API → http://localhost:8000/docs

MySQL → localhost:3307

🧩 Environment Variables
Variable	Description	Example
DB_HOST	MySQL server host	db
DB_USER	MySQL username	eventuser
DB_PASSWORD	MySQL password	eventpass
DB_NAME	MySQL database name	eventdb
DB_PORT	MySQL port	3306

You can define them in a .env file or via Render/DigitalOcean environment settings.

🧰 Backend API Endpoints
Method	Endpoint	Description
GET	/events	Get all events
POST	/events	Create an event
GET	/registrations	Get all registrations
POST	/registrations	Register a user

📘 Docs available at:
👉 http://localhost:8000/docs


🖼️ Preview
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/0272ebdc-f46b-4af2-8301-cef54cc295a7" />

