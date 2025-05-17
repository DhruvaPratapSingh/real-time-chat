# 💬 GupShup – Real-Time Live Chat Application

**GupShup** is a modern, real-time chat application that allows users to communicate instantly through private messages. It’s designed for speed, simplicity, and seamless communication, making it ideal for both desktop and mobile users.

---

## 🧩 Key Features

- ✅ **Real-Time Messaging** using WebSockets (Socket.IO)
- ✅ **One-on-One Chats**
- ✅ **User Authentication** (JWT)
- ✅ **Message Seen / Delivered Indicators**
- ✅ **Online/Offline Status**
- ✅ **Typing Indicators**
- ✅ **Responsive UI** (Mobile + Desktop)
- ✅ **Emoji Support**
- ✅ **Push Notifications**
- ✅ **Various Themes**

---

## 🛠️ Tech Stack

### 🧩Frontend Stack:
- *React* (via Vite) ⚡ – Fast SPA development
- *React Router DOM* – Routing and navigation
- *Axios* – API requests with token support
- *Zustand* – Lightweight state management
- *React Hot Toast* – Elegant toast notifications
- *Lucide React* – Modern icon pack
- *Tailwind CSS* – Utility-first styling framework
- *DaisyUI* – UI components for Tailwind

### 🚀 Backend Stack:
- *Node.js + Express.js* – Backend server and API
- *MongoDB + Mongoose* – NoSQL database & ODM
- *Socket.IO* – WebSocket-based real-time chat
- *Cloudinary* – Media upload & CDN storage
- *Cors* – Cross-origin resource sharing
- *Dotenv* – Manage environment variables
- *Cookie Parser* – Parse HTTP cookies
- *JSON Web Token (JWT)* – User authentication
- *BcryptJS* – Password hashing

---

## 📁 GupShup – Folder Structure

### **📦Frontend**
```
frontend/
├── node_modules/                  # Installed frontend dependencies
├── public/
│   ├── avatar.png                     # Default avatar image
│   └── chatlogo.png                   # Chat app logo
│
├── src/
│   ├── components/                   # Reusable UI components
│   │   ├── skeletons/                    # Skeleton loading components
│   │   │   ├── MessageSkeleton.jsx
│   │   │   ├── SidebarSkeleton.jsx
│   │   │   └── AuthImagePattern.jsx     # Pattern shown on auth screens
│   │   ├── ChatContainer.jsx            # Main chat area
│   │   ├── ChatHeader.jsx               # Header of chat window
│   │   ├── MessageInput.jsx            # Input field to send messages
│   │   ├── Navbar.jsx                   # Top navigation bar
│   │   ├── NoChatSelected.jsx          # Placeholder view when no chat selected
│   │   └── Sidebar.jsx                 # Sidebar showing user chats
│   │
│   ├── constants/
│   │   └── index.js                    # Static config and constants
│   │
│   ├── lib/
│   │   ├── axios.js                    # Axios instance setup (with baseURL & interceptors)
│   │   └── utils.js                    # Utility functions
│   │
│   ├── pages/                         # Page-level views
│   │   ├── HomePage.jsx               # Main page after login
│   │   ├── LoginPage.jsx              # Login screen
│   │   ├── ProfilePage.jsx            # User profile and settings
│   │   ├── SettingsPage.jsx           # General app settings
│   │   └── SignUpPage.jsx             # Sign up screen
│   │
│   ├── store/                         # Global state management (e.g. Zustand, Redux, etc.)
│
│   ├── App.jsx                        # App root component
│   ├── index.css                      # Global styles
│   └── main.jsx                       # Entry point (renders <App />)
│
├── index.html                        # HTML entry for Vite
├── package.json                      # Project metadata and scripts
├── package-lock.json                 # Locked package versions
├── postcss.config.js                 # PostCSS config (used by Tailwind)
├── tailwind.config.js                # TailwindCSS customization
├── vite.config.js                    # Vite bundler config
├── eslint.config.js                  # ESLint configuration
└── README.md                         # Documentation file

```

### **📦Backend**
```
backend/
├── node_modules/                 # Installed backend dependencies
├── src/
│   ├── controllers/              # Business logic for routes
│   │   ├── auth.controller.js        # Handles user login/register
│   │   └── message.controller.js     # Manages message-related logic
│   │
│   ├── lib/                     # Core utilities and 3rd-party setup
│   │   ├── cloudinary.js            # Cloudinary upload config (images/media)
│   │   ├── db.js                    # MongoDB connection setup
│   │   ├── socket.js                # Socket.IO real-time logic
│   │   └── utils.js                # Helper functions
│   │
│   ├── middleware/              # Express middleware
│   │   └── auth.middleware.js       # JWT or session-based auth checks
│   │
│   ├── models/                  # Mongoose models (MongoDB schemas)
│   │   ├── message.model.js         # Message schema
│   │   └── user.model.js            # User schema
│   │
│   ├── routes/                  # Express route definitions
│   │   ├── auth.route.js            # /api/auth (register/login)
│   │   └── message.route.js         # /api/messages (send/get)
│   │
│   ├── seeds/                   # DB seeding scripts
│   │   └── user.seed.js             # Seed dummy users
│   │
│   └── index.js                 # App entry point (express + socket server)
│
├── .env                         # Environment variables (PORT, DB_URI, etc.)
├── package.json                 # Backend project metadata and scripts
├── package-lock.json            # Locked versions of npm packages

```
## 📸 Screenshots



