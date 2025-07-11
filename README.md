URL Shortener 

A full-stack URL shortening web application that allows users to shorten long URLs and redirect them using custom, unique short links. Built with a modular architecture using React, Node.js, and MongoDB.


## 💡 Overview

This project was built to demonstrate strong frontend-backend integration, API handling, and deployment-readiness. The system mimics real-world services like TinyURL and Bitly, offering simple UX and robust performance under the hood.

---

##  Key Features

- Convert long URLs into custom, shortened links
- Automatic redirection using unique hashes
- RESTful API design with Express.js
- Responsive UI with React + Tailwind CSS
- MongoDB integration for persistent link storage
- Error handling, loading states, and form validation
- Easily deployable on Render, Vercel, or AWS

##  Tech Stack

| Layer         | Technology            |
|---------------|------------------------|
| Frontend      | React, Tailwind CSS    |
| Backend       | Node.js, Express.js    |
| Database      | MongoDB (via Mongoose) |
| API Protocol  | REST                   |
| Dev Tools     | Axios, Git, Vite, npm  |

---

##  Installation

### Clone the Repository 
```bash
git clone https://github.com/Raihana-Afshan/url-shortner-raihana.git
cd url-shortner-raihana

Setup Server
cd server
npm install


Create a .env file inside server folder:

MONGO_URI=your-mongodb-uri
BASE_URL=http://localhost:5000
PORT=5000


Start the server:
npm run dev

Setup Client:
cd ../client
npm install
npm run dev
Visit http://localhost:5173 in your browser.

Learnings:

Structuring a MERN stack application from scratch

Designing and testing RESTful endpoints

Connecting frontend to backend with Axios

Using Tailwind for responsive, modern UI

Managing async operations and MongoDB integration

Preparing an app for deployment with environmental configs


Folder Structure
url-shortner-raihana/
├── client/        # React frontend
├── server/        # Node.js backend
└── README.md

Created with by Raihana Afshan
raihanaafshan29@gmail.com


