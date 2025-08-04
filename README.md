
# JobConnect Pro — Enterprise Job Portal Platform

JobConnect Pro is a full-featured recruitment system built with the MERN stack. It enables job seekers to discover and apply for jobs, while employers can post listings, manage applications, and hire efficiently.

---

## Overview

This platform offers secure role-based authentication, smart job matching, real-time messaging, and document uploads. It supports the full recruitment lifecycle with a modular, scalable architecture.

---

## Architecture

- MERN stack following MVC pattern
- RESTful API with Express.js
- JWT authentication with refresh token support
- Cloudinary for media/document handling
- Socket.io for real-time communication

---

## Features

- Advanced job search with dynamic filters
- Role-based dashboards for job seekers and employers
- Job application tracking system
- Real-time chat between employers and candidates
- Resume upload and parsing with skill matching

---

## Tech Stack

- **Frontend:** React.js, Redux, Tailwind CSS  
- **Backend:** Node.js, Express.js, MongoDB  
- **Authentication:** JWT (access + refresh)  
- **Media Handling:** Cloudinary  
- **Real-Time:** Socket.io

---

## Highlights

- Built real-time messaging using Socket.io  
- Integrated secure resume uploads via Cloudinary  
- Designed job-matching algorithm tested across 50+ mock listings  
- Presented working prototype with positive technical feedback

---

## Project Structure

```

jobconnect-pro/
├── client/               # React frontend
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       └── App.js
├── server/               # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
└── README.md

````

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/AmaedaQ/job-portal.git
cd job-portal
````

### 2. Install Dependencies

```bash
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
```

### 3. Environment Variables

Create a `.env` file in the `/server` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4. Run Development Servers

```bash
# Start backend
cd server
npm run dev

# Start frontend
cd ../client
npm start
```

---

## License

MIT License

```


Let me know, and I’ll generate them in the same clean, no-fluff style.
```
