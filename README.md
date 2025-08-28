
# ⚡Courseify LMS

Courseify LMS 🎓 is a modern Learning Management System designed to make online education more accessible, engaging, and scalable. It empowers instructors 👩‍🏫 to create and manage courses easily while providing students 👨‍🎓 with an interactive and user-friendly learning experience.

Built with the MERN stack ⚡ (MongoDB, Express.js, React.js, Node.js) and styled using Tailwind CSS 🎨, Courseify LMS delivers a fast, responsive, and secure platform for online learning.

# 🔑 Key Highlights

👩‍💻 **Role-based Dashboards** – Separate portals for students and instructors.

📚 **Course Management** – Create, update, and manage courses seamlessly.

📈 **Progress Tracking** – Students can monitor their learning journey in real time.

🔐 **Secure Authentication** – JWT-based login & access control for enhanced safety.

💳 **Payment Integration** – Smooth enrollment via Stripe .

🎥 **Video-based Learning** – Support for lectures, documents, and rich media.

📊 **Analytics Dashboard** – Insights into performance and course engagement.

 # 🎯 Motivation
With the growing shift towards digital education 🌍, I wanted to build a platform that reflects real-world challenges of e-learning systems.
Courseify LMS demonstrates my ability to:
🖥️ Develop full-stack MERN applications.

🎨 Build clean, responsive frontend UIs using React + Tailwind.

⚙️ Create scalable and secure REST APIs with Express & Node.

🔒 Implement authentication & authorization best practices.

🚀 Deploy production-ready apps on Vercel (Frontend) and Render/Heroku (Backend).

This project is a step towards contributing to the future of online education 💡 while showcasing my skills as a Software Engineer Fresher 👨‍💻.

## 🛠 Tech Stack  

- **Frontend:** ⚛️ React, 🎨 Tailwind CSS, React Router  
- **Backend:** 🟢 Node.js, 🚀 Express  
- **Database:** 🐘 MongoDB   
- **Authentication & Billing:** 🔑 Clerk  
- **File Storage:** ☁️ Cloudinary
- **Payment Authentication :**💳 Stripe
- **Deployment:** ▲ Vercel (Frontend), ▲ Vercel (Backend)  


## 📂 Project Structure  

```bash
Courseify_LMS/
│── client/ # React frontend
│ ├── public/ # Static assets
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page components (Dashboard, Courses, etc.)
│ │ ├── utils/ # Helpers and constants
│ │ ├── services/ # API calls (Axios)
│ │ └── App.js # Main App entry
│ └── package.json # Frontend dependencies
│
│── server/ # Node.js backend
│ ├── config/ # DB & environment configs
│ ├── controllers/ # Request handlers
│ ├── models/ # MongoDB schemas
│ ├── routes/ # API routes
│ ├── middleware/ # Auth & error handlers
│ └── server.js # Backend entry point
│
│── .env # Environment variables
│── package.json # Root dependencies (if any)
│── README.md # Project documentation
```
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file
# ⚙️ Environment Variables  

Create a `.env` file inside the **server** folder and add:  

```env
# Currency setup for Stripe
CURRENCY = ''

#Database Connection
MONGODB_URI = ''

#Clerk connection 
CLERK_WEBHOOK_SECRET = ''
CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

#Cloudinary Connection
CLOUDINARY_NAME = ""
CLOUDINARY_API_KEY = ""
CLOUDINARY_SECRET_KEY = ""

STRIPE_PUBLISHABLE_KEY = ''
STRIPE_SECRET_KEY = ''

STRIPE_WEBHOOK_SECRET = ""
 ```
## 💻 Installation  

Follow these steps to run the project locally:  
```bash
git clone https://github.com/Anmol-78/Courseify_LMS.git
cd Courseify_LMS

## Install frontend dependencies
cd frontend
npm install

## Install backend dependencies
cd server
npm install

## Start backend (in server folder)
npm run server

## Start frontend (in client folder)
npm run dev
```
🚀 Production Deployment

You can deploy Courseify LMS to production using Vercel for both frontend and Backend.
```bash
```
# 1. Deploy Backend (Server)

Push your code to GitHub.

Create a new project on VErcel

Connect your repo and deploy the server/ folder.

Add your environment variables (from .env) in the vercel dashboard.

After deployment, you’ll get a live API URL (e.g., https://courseify-lms-backend.vercel.app/).
```
```
# 2. Deploy Frontend (Client)

Go to Vercel and create a new project.

Import your repo and select the client/ folder.

Set environment variables (like API base URL, Clerk keys, Cloudinary keys).

Deploy! 🎉

Your app will be live at something like https://courseify-lms-frontend.vercel.app/
```
```


## 🎥 Demo  

### 🌐 Live Demo  
👉 [Courseify_LMS Live Live](https://courseify-lms-frontend.vercel.app/)  

## 📬 Contact

Created with ❤️ by Anmol Goyal



