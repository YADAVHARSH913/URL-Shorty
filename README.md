# 🌐 URL-Shorty

A modern **URL Shortener Web App** built with the **MERN stack (MongoDB, Express, React, Node.js)**.  
It allows users to shorten long URLs, manage them via a personal dashboard, and track click statistics — all with a clean UI supporting **dark/light mode**.  

---

## 🚀 Features

- 🔑 **User Authentication** (Signup / Login with JWT)  
- ✂️ **Shorten URLs** instantly  
- 📊 **Click Tracking** for each short URL  
- 🗂 **Personal Dashboard** to manage all links  
- 🌓 **Dark / Light Mode** toggle  
- 🔒 **Secure Passwords** with hashing  

---

## 🛠 Tech Stack

**Frontend**: React, React Router, Axios, CSS / Tailwind (if used)  
**Backend**: Node.js, Express.js  
**Database**: MongoDB (Mongoose ODM)  
**Authentication**: JWT, bcrypt  
**Other**: dotenv, cors  

---

## 📂 Folder Structure

URL-Shorty/
├── backend/
│ ├── controllers/ # Route logic
│ ├── models/ # MongoDB models
│ ├── routes/ # Express routes
│ ├── middleware/ # Auth middlewares
│ ├── server.js # App entry point
│ └── package.json
│
├── frontend/
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # App pages
│ │ ├── utils/ # Helper functions
│ │ ├── App.js
│ │ └── index.js
│ ├── public/
│ └── package.json
│
├── .gitignore
├── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

Follow these steps to run locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YADAVHARSH913/URL-Shorty.git
cd URL-Shorty
2️⃣ Install Dependencies
Backend:

bash
Copy code
cd backend
npm install
Frontend:

bash
Copy code
cd ../frontend
npm install
3️⃣ Configure Environment Variables
Create a .env file inside backend/ with the following:

ini
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:3000
4️⃣ Run the Application
Start backend:

bash
Copy code
cd backend
npm start
Start frontend:

bash
Copy code
cd ../frontend
npm start
Frontend runs on http://localhost:3000
Backend runs on http://localhost:5000

🎯 Usage
Open http://localhost:3000 in browser

Signup / Login

Paste a long URL and shorten it ✂️

Share the short link and track clicks in your dashboard

Toggle dark/light mode as you like 🌙☀️

📸 Screenshots / Demo
(Add screenshots or a live demo link here once hosted, e.g. on Vercel / Netlify + Render / Railway)

🤝 Contributing
Contributions are welcome! Follow these steps:

Fork the repo

Create a new branch (git checkout -b feature/your-feature)

Commit changes (git commit -m "Add new feature")

Push to branch (git push origin feature/your-feature)

Open a Pull Request

📜 License
This project is licensed under the MIT License.
Feel free to use and modify it as per your needs.

👤 Author
Harsh Yadav
