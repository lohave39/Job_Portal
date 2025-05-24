# 🚀 Job Portal - MERN Stack Project

A full-featured **Job Portal** built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). Users can register, log in, post jobs, apply with resumes, and manage applications. It also integrates **Cloudinary** for file uploads and **Gmail SMTP** for email notifications.

---

## 🌐 Live Demo & GitHub

- 🔗 **GitHub Repo**: [Job_Portal](https://github.com/lohave39/Job_Portal)
- 🎬 **Demo Video**: [Watch Now](https://drive.google.com/file/d/1Hcebo81e-JDOL6bP0WMjNtwE1GEAX-DZ/view?usp=sharing)

---

## 🧰 Tech Stack

- 🟢 **MongoDB** – Database
- ⚙️ **Express.js** – Backend Framework
- ⚛️ **React.js** – Frontend Library
- 🟣 **Node.js** – Server Environment
- ☁️ **Cloudinary** – File & Image Uploads
- 📩 **Gmail SMTP** – Email Notifications
- 🔐 **JWT** – Authentication

---

## 🛠️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/lohave39/Job_Portal.git
cd Job_Portal
2️⃣ Backend Setup
📂 Navigate to Backend Folder
bash
Copy
Edit
cd backend
npm install
🔐 Create .env File
Create a .env file in the backend directory and add:
PORT=4000

MONGO_URI=mongodb+srv://<your-db-url>

JWT_SECRET_KEY=your_jwt_secret
COOKIE_EXPIRE=5
JWT_EXPIRE=1h

FRONTEND_URL=http://localhost:5173

EMAIL=your_email@gmail.com
EMAIL_PASSWORD=your_email_password

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_SERVICE=gmail
SMTP_MAIL=your_email@gmail.com
SMTP_PASSWORD=your_email_password
3️⃣ Frontend Setup
📂 Navigate to Frontend Folde
cd ../frontend
npm install
cd ../frontend
npm install
cd ../frontend
npm install
▶️ Run Frontend
npm run dev
