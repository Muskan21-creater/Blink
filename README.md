# Blink – Anonymous Real-Time Chat

**Blink** is a web-based anonymous chat application designed to make real-time conversations simple, private, and temporary. Users can connect and exchange messages without sharing personal identities, creating a lightweight chatting experience focused on privacy and simplicity.

## ✨ Features

- **Anonymous Chatting:** Connect and communicate without displaying personal identity.
- **Real-Time Messaging:** Exchange messages instantly using Socket.IO.
- **Temporary Conversations:** Designed around short-lived chat experiences.
- **Simple Interface:** Clean and minimal user interface for easy navigation.
- **Responsive Design:** Built with modern frontend technologies.

## 🛠️ Tech Stack

**Frontend**
- React
- TypeScript
- Vite
- Tailwind CSS

**Backend**
- Node.js
- TypeScript
- Socket.IO

**Tools**
- Git & GitHub
- Vercel

## 📁 Project Structure

```text
Blink/
├── client/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── hooks/
│       ├── pages/
│       ├── socket/
│       ├── store/
│       └── App.tsx
│
├── server/
│   └── src/
│       ├── database.ts
│       ├── server.ts
│       └── utils.ts
│
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js
- pnpm
- Bun

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Muskan21-creater/Blink.git
cd Blink
```

2. Install frontend dependencies:

```bash
cd client
pnpm install
```

3. Install backend dependencies:

```bash
cd ../server
bun install
```

4. Configure the environment variables using the provided `server/.env.sample` file.

5. Start the frontend and backend using the development scripts defined in their respective `package.json` files.

## 🌐 Live Demo

[Try Blink](https://nixchat.vercel.app/)

## 🎯 Project Objective

The objective of Blink is to explore real-time web communication, client-server interaction, and temporary anonymous conversations through a modern web application.

## 👩‍💻 Author

**Muskan Ahamed**

GitHub: [Muskan21-creater](https://github.com/Muskan21-creater)

---

