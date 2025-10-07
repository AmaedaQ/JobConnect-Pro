
<h1 align="center">💼 JobConnect Pro — Enterprise Recruitment Platform</h1>

<p align="center">
  <strong>Production-grade job portal built on the MERN stack</strong><br/>
  Scalable architecture, role-based access, real-time messaging, and AI-assisted job matching.
</p>

<p align="center">
  <a href="https://mern.io"><img src="https://img.shields.io/badge/Stack-MERN-4DB33D?logo=mongodb&logoColor=white" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" /></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-18+-339933?logo=node.js&logoColor=white" /></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-18+-61DAFB?logo=react&logoColor=white" /></a>
</p>

---

## 🚀 Core Features

- 🔍 **Smart Job Matching** — Skill-based ranking and filters  
- 👥 **Role-Based Dashboards** — Separate flows for employers and candidates  
- 💬 **Real-Time Chat** — Powered by Socket.io  
- 📄 **Resume Management** — Upload, parse, and match via Cloudinary  
- 🔐 **Secure Auth** — JWT (access + refresh) with middleware protection  

---

## 🧩 System Overview

| Layer | Stack |
|-------|-------|
| Frontend | React 18, Redux, Tailwind CSS |
| Backend | Node.js, Express.js (MVC pattern) |
| Database | MongoDB (Mongoose ORM) |
| Auth | JWT Tokens |
| Real-Time | Socket.io |
| Media | Cloudinary |

---

## 🏗 Highlights

- Engineered real-time messaging with **Socket.io**  
- Integrated secure resume handling with **Cloudinary**  
- Built modular job-matching engine tested on 50+ sample listings  
- Delivered fully containerized, **scalable MERN** architecture  

---

## 📁 Project Structure

```

jobconnect-pro/
├── client/           # React frontend
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       └── App.js
├── server/           # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
└── README.md

````

---

## ⚙️ Setup

```bash
# Clone repository
git clone https://github.com/AmaedaQ/job-portal.git
cd job-portal

# Install dependencies
cd server && npm install
cd ../client && npm install
````

### 🔧 Environment Variables

Create a `.env` file inside `/server`:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### ▶️ Run Application

```bash
# Backend
cd server && npm run dev

# Frontend
cd ../client && npm start
```

---

## 📜 License

MIT © Amaeda Qureshi


