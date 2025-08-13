# Patient Portal

A full stack Patient Portal System built with React for the frontend, Node.js + Express.js for the backend and PostgreSQL is used for database.  
It allows users to upload, list, download, make favorite and delete documents with scalable architecture.

# Tech Stack

- Frontend  
- React (Vite)  
- Tailwind CSS  
- Axios 

- Backend  
- Node.js  
- Express.js  
- Multer  
- PostgreSQL  

- Deployment  
- Backend hosted on Render  
- PostgreSQL on Render  
- Ready for migration to AWS S3 for file storage  
- Frontend hosted on Vercel  

# Features

- Upload Documents (PDF only)
- List Documents with category counts
- Download Documents
- Mark as Favorite
- Delete Documents
- Statistics by Category
- Fast Rendering with React Hooks

# Installation & Setup

# Clone Repository
- git clone https://github.com/Umesh594/patient_portal.git
# Backend Setup
- cd backend
- npm install
- Create .env file with:
- PG_USER
- PG_HOST
- PG_DATABASE
- PG_PASSWORD
- PG_PORT
- Run backend:
- node server.js
# Frontend Setup
- cd frontend
- npm install
- npm run dev

# API Calls
- curl -X POST https://patient-portal-ixd8.onrender.com/documents/upload
- curl -X GET  https://patient-portal-ixd8.onrender.com/documents
- curl -X GET  https://patient-portal-ixd8.onrender.com/documents/:id/download
- curl -X DELETE https://patient-portal-ixd8.onrender.com/documents/:id
- curl -X POST https://patient-portal-ixd8.onrender.com/documents/:id/favorite
