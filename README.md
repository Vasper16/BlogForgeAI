# 🚀 BlogForgeAI

**BlogForgeAI** is a powerful, full-stack blog publishing platform built on the **MERN stack** and enhanced by **Google's Gemini API**. It offers comprehensive markdown blogging, rich media post support, and unique **AI-powered blog generation from just a title input**. The platform features secure **authentication**, an intuitive **admin dashboard**, a robust **comment system**, and **real-time search**, all within a responsive, mobile-first UI.

> ✨ Think of it as a smart, scalable, and AI-driven alternative to traditional blogging platforms like Medium, designed and built by developers.

---

## 🧠 Key Features

* 🔐 **Secure Authentication** – Robust user sign-up/login with **JWT** & **bcrypt**.
* 📝 **Blog Management (CRUD)** – Seamless creation, editing, deletion, and publishing of markdown-supported posts.
* 🧠 **AI Blog Generation** – Create complete blog posts from a simple title using the **Gemini API**.
* 🧲 **Dynamic Tag Filtering** – Efficiently filter posts by topics (e.g., React, Node.js, AI).
* 🔍 **Real-time Search** – Instant search across blog titles and content for quick discovery.
* 📊 **Admin Dashboard** – Centralized control for viewing statistics and managing blogs, users, and comments.
* 👀 **Post View Counter** – Tracks and displays blog popularity.
* 💬 **Interactive Comments Section** – Enhances reader engagement with feedback threads.
* 👏 **Clap/Like Functionality** – Allows users to express appreciation for content.
* 🗂 **Draft & Publish Toggle** – Enables saving work-in-progress before public publishing.
* 🌐 **Responsive UI** – Optimized for a seamless experience across all devices (mobile & desktop).
* 🔑 **Role-Based Access Control** – Differentiated views and functionalities for users and administrators.
* 🤖 **Advanced AI Capabilities (Gemini-Powered)** –
    * **Automated Comment Replies:** Generate intelligent responses to comments.
    * **Content Summarization:** Create concise summaries of blog posts.
    * **Idea to Post Generation:** Streamline content creation from initial prompts to full articles.

---

## 🛠️ Tech Stack

| Layer       | Tech Used                                |
|-------------|------------------------------------------|
| Frontend    | React, Tailwind CSS, Axios, Markdown     |
| Backend     | Node.js, Express.js, MongoDB             |
| Auth        | JWT, bcrypt                              |
| AI API      | Gemini (Google Generative AI)            |
| Database    | MongoDB Atlas                            |
| Deployment  | Vercel (Frontend), Render/Heroku (API)   |
| Dev Tools   | ESLint, Prettier, VS Code                |

---

## 📁 Project Structure

```BlogForgeAI/
├── backend/                  # Node.js + Express backend API
│   ├── routes/               # API endpoints for authentication, blogs, comments, AI
│   ├── models/               # Mongoose schemas for data models
│   ├── controllers/          # Business logic for API endpoints
│   └── server.js             # Backend entry point
│
├── frontend/                 # React client application
│   ├── src/
│   │   ├── components/       # Reusable UI components (e.g., Navbar, cards, editor)
│   │   ├── pages/            # Page-level components (e.g., Login, Dashboard, BlogPost)
│   │   └── App.jsx           # Main React application component
│   └── package.json          # Frontend dependencies
│
├── .gitignore                # Specifies intentionally untracked files to ignore
├── README.md                 # Project overview and documentation
└── package.json              # Root-level dependencies (if mono-repo setup, otherwise remove)

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



