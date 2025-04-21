Job Portal - MERN Stack Application
A complete job portal web application where users can register as job seekers or employers, post jobs, apply with resumes, and manage applications.

🌐 Live Links
Frontend: https://ashish-task-job-portal.netlify.app

Backend API: https://job-portal-main-8yob.onrender.com

GitHub Repository: https://github.com/lohave39/Job_Portal

Demo Video: Link to video <!-- Replace with actual link -->

🛠️ Setup Instructions
Prerequisites
Node.js and npm

MongoDB Atlas account (or local MongoDB)

Clone the Repo
bash
Copy
Edit
git clone https://github.com/lohave39/Job_Portal.git
cd Job_Portal
Setup Backend
bash
Copy
Edit
cd backend
npm install
Create a .env file inside the backend folder and add the following:

env
Copy
Edit
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
To start the backend server:

bash
Copy
Edit
npm start
Setup Frontend
bash
Copy
Edit
cd frontend
npm install
To run the frontend locally:

bash
Copy
Edit
npm run dev
⚙️ Features
👤 User Registration & Login

🧑‍💼 Employer Job Posting

📑 Job Seeker Applications with Resume Upload (via Cloudinary)

✅ Application Tracking (Job Seeker & Employer Side)

🧾 Protected Routes and JWT Auth

💾 MongoDB for persistent storage

🌐 CORS enabled between Netlify frontend and Render backend

📷 Screenshots / Demo
<!-- Add screenshots or demo GIF/video link here -->
