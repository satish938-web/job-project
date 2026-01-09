💼 Job Portal Application (MERN Stack)

A full-stack Job Portal web application built using the MERN stack where users can search and apply for jobs, upload resumes, and manage profiles, while admins can manage companies, jobs, and applicants.

🚀 Features
👤 User

Signup & Login with JWT Authentication

Update profile & upload resume

Browse, search, and filter jobs

Apply for jobs

View applied jobs

🛠️ Admin

Create & manage companies

Post, update, and delete jobs

View applicants for jobs

Update applicant status

Admin-only protected routes

🧰 Tech Stack
Frontend

React.js (Vite)

Redux Toolkit

ShadCN UI

Framer Motion

Backend

Node.js

Express.js

MongoDB

Mongoose

Other Tools

JWT Authentication

Multer (File Upload)

Postman (API Testing)

🗂️ Project Structure
job-portal/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── redux/
│   ├── hooks/
│   └── components/
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/job-portal-mern.git

2️⃣ Backend Setup
cd backend
npm install
npm run dev


Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev

🔐 Authentication

JWT-based authentication

Role-based authorization (User / Admin)

Protected routes for admin and authenticated users

📦 State Management

Redux Toolkit

Persistent store for user session

📸 Screens (Optional)

Add screenshots of Home, Jobs, Admin Dashboard here

📌 Future Improvements

Email notifications

Pagination & sorting

Resume preview

Deployment (AWS / Vercel)

👨‍💻 Author

Satish
MERN Stack Developer
