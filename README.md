# codealpha-task2

Features Implemented
👤 User Profiles

📝 Posts & Comments

❤️ Like & Follow System

🔐 User Authentication (Register/Login)

🔍 View others' profiles and interact socially

🧰 Tech Stack
🔹 Frontend
HTML5

CSS3

JavaScript (Vanilla)

🔹 Backend
Node.js + Express.js (or Django, if used)

🔹 Database
MongoDB (with Mongoose) (or PostgreSQL/MySQL if Django)

🔹 Libraries/Tools
bcrypt (password hashing)

JWT (JSON Web Tokens for auth)

Express-session / CORS

Multer (for profile pic uploads - optional)

📁 Folder Structure
pgsql
Copy
Edit
social-media-platform/
├── client/
│   ├── index.html
│   ├── login.html
│   ├── profile.html
│   ├── style.css
│   └── script.js
│
├── server/
│   ├── models/
│   │   ├── User.js
│   │   ├── Post.js
│   │   └── Comment.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── posts.js
│   │   └── users.js
│   ├── controllers/
│   ├── config/
│   └── server.js
│
├── .env
├── README.md
└── package.json
