# 🌙 Moodly

Welcome to **Moodly**, your personal space to express thoughts, share moods, and connect with the vibe! Whether it’s a text snippet, a spontaneous update, or an image of your moment — Moodly lets you post it, like it, and live it.

---

## ✨ Features

- 🔐 User Authentication (Register & Login)
- 🧠 JWT-based session management with cookies
- 🖼️ Upload and update profile pictures
- 💬 Create, edit, and delete text-based posts
- ❤️ Like / Unlike posts
- 📄 View all user posts on a universal feed
- 👤 Personal profile with post history

---

## 🛠 Tech Stack

### 👨‍💻 Backend:
- **Node.js**
- **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for authentication
- **Bcrypt** for password hashing
- **Cookie-Parser** for session handling
- **Multer** for image upload

### 🎨 Frontend:
- **HTML5**
- **TailwindCSS**
- **EJS** (Embedded JavaScript Templates)

---

## 🚀 Installation

```bash
# 1. Clone the repo
git clone https://github.com/roni2668/moodly.git
cd moodly

# 2. Install dependencies
npm install

# 3. Create a `.env` file (or set config) for:
#    - MONGODB_URI
#    - JWT_SECRET

# 4. Run the server
node app.js
