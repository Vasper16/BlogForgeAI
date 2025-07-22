# 🚀 BlogForgeAI

**BlogForgeAI** is a powerful, full-stack blog publishing platform built with the MERN stack and powered by the Gemini API. It supports markdown blogging, rich media posts, and full AI-powered blog generation from a simple title input. The platform includes features like secure authentication, admin dashboard, comment system, and real-time search — all wrapped in a responsive, mobile-first UI.

> ✨ Think of it as a smart, scalable alternative to Medium — built with AI, by developers.

---

## 🧠 Key Features

- 🔐 **Authentication** – Secure sign-up/login with JWT & bcrypt
- 📝 **Blog CRUD** – Create, edit, delete, and publish posts with markdown
- 🧠 **AI Blog Generator** – Generate complete blog posts using Gemini API
- 🧲 **Tag Filtering** – Filter posts based on topics like React, Node.js, etc.
- 🔍 **Real-time Search** – Search blog titles and content live
- 📊 **Admin Dashboard** – View stats, manage blogs, users, and comments
- 👀 **Post View Counter** – Track blog popularity
- 💬 **Comments Section** – Engage readers with feedback threads
- 👏 **Clap/Like Button** – Let users appreciate content
- 🗂 **Draft & Publish Toggle** – Save work in progress before publishing
- 🌐 **Responsive UI** – Seamlessly optimized for mobile & desktop
- 🔑 **Role-Based Routes** – Different views for users/admins
- 🧠 **AI-Powered Comment Reply & Summary** – Auto-reply and summarize via Gemini

---

## 🛠️ Tech Stack

| Layer       | Tech Used                             |
|-------------|----------------------------------------|
| Frontend    | React, Tailwind CSS, Axios, Markdown |
| Backend     | Node.js, Express.js, MongoDB          |
| Auth        | JWT, bcrypt                           |
| AI API      | Gemini (Google Generative AI)         |
| Database    | MongoDB Atlas                         |
| Deployment  | Vercel (Frontend), Render/Heroku (API)|
| Dev Tools   | ESLint, Prettier, VS Code             |

---

## 📁 Folder Structure

BlogForgeAI/
├── backend/                 # Node.js + Express backend
│   ├── routes/              # Auth, blog, comment, AI routes
│   ├── models/              # Mongoose schemas
│   ├── controllers/         # API logic
│   └── server.js            # Backend entry point
│
├── frontend/                # React client app
│   ├── src/
│   │   ├── components/      # Navbar, cards, editor, etc.
│   │   ├── pages/           # Login, Dashboard, BlogPost, etc.
│   │   └── App.jsx
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json             # Root-level (if mono-repo setup)

---

## 🧪 How to Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/Vasper16/BlogForgeAI.git
cd BlogForgeAI

2. Setup Backend
cd backend
npm install
# Add .env file with MONGO_URI and JWT_SECRET
npm run dev

3. Setup Frontend
cd frontend
npm install
npm run dev

📌 AI Features Powered by Gemini : 
✨ Generate blog content using title prompts

🧠 Generate blog summaries

💬 Auto-generate replies to comments

🧠 Plan blog ideas via prompt-to-post

🔗 Project Links
💻 Live: Coming Soon

📦 Repo: github.com/Vasper16/BlogForgeAI



