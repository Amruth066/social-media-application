# 📱 SocialSphere

**SocialSphere** is a full-featured social media platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It supports real-time messaging, markdown-enabled content, nested comments, JWT authentication, and more. The application is fully responsive and designed for scalability and performance.

---

## 🚀 Features

### 📝 Posts
- Create, read, update, and delete posts
- Markdown support for post content
- Like and unlike functionality
- View users who liked a post
- Sort by like count, comment count, and date created
- Infinite scrolling for post feeds
- Search for posts by title

### 💬 Comments
- Nested comments with full CRUD support
- Markdown support
- Profanity filtering
- Cooldown between comments to prevent spam

### 🔐 Authentication
- Sign up and login using JWT
- Password hashing using bcrypt
- Protected routes

### 🙋‍♂️ User Profiles
- View other users' profiles and their posts, liked posts, and comments
- Editable user bio

### 📬 Real-time Private Messaging
- Socket.IO-based messaging system
- One-on-one private chat
- Optional message history persistence

### 💅 UI/UX
- Fully responsive layout (mobile-first)
- Clean and intuitive interface
- Smooth user experience with infinite scroll, loading states, and modals

---

## 🛠️ Tech Stack

| Layer        | Technology |
|--------------|------------|
| Frontend     | React.js, Tailwind CSS, React Router, Axios, React Markdown |
| Backend      | Node.js, Express.js, MongoDB, Mongoose |
| Real-time    | Socket.IO |
| Authentication | JWT, bcrypt |
| Dev Tools    | Docker, Nginx, GitHub Actions (CI/CD), ESLint, Prettier |
| Security     | Helmet, CORS, Rate Limiting |
| Utility      | bad-words (profanity filter), marked/react-markdown (Markdown support) |

---

## 📂 Folder Structure

```bash
SocialSphere/
├── client/               # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       ├── services/
│       └── App.jsx
├── server/               # Node.js Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── docker-compose.yml
├── README.md
└── .env
