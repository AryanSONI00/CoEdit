# CoEdit

<p align="center">
  <img src="https://img.shields.io/badge/Realtime-Collaboration-brightgreen" alt="Realtime Collaboration"/>
  <img src="https://img.shields.io/badge/Editor-Monaco-blue" alt="Monaco Editor"/>
  <img src="https://img.shields.io/badge/Socket.IO-4.x-ffca28" alt="Socket.IO"/>
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"/>
</p>

> **Code, Sync, Collaborate**

CoEdit is a modern, real-time collaborative code editor. Instantly code together, chat, and manage files with your team—right from your browser.

---

## ✨ Features

-   **Real-time Code Editing**: Collaborate live with others using the Monaco Editor (VSCode experience in the browser).
-   **Multi-user Collaboration**: See who’s online, join rooms, and work together seamlessly.
-   **Live Chat**: Communicate instantly with your team while coding.
-   **File & Directory Management**: Create, rename, update, and delete files and folders collaboratively.
-   **Realtime Drawing/Whiteboard**: Sketch ideas together with integrated drawing tools (powered by tldraw).
-   **Presence & Status**: See who’s typing, online, or offline in real time.
-   **Beautiful UI**: Built with React and Tailwind CSS for a clean, modern look.

---

## 🛠️ Tech Stack

-   **Frontend**: React, Vite, Tailwind CSS, Monaco Editor, tldraw
-   **Backend**: Node.js, Express, Socket.IO
-   **Other**: Docker, ESLint, Prettier

---

## 🚀 Getting Started

### Prerequisites

-   Node.js (v18+ recommended)
-   npm or yarn

### 1. Clone the repository

```bash
git clone https://github.com/AryanSONI00/CoEdit.git
cd coedit
```

### 2. Install dependencies

#### Client

```bash
cd client
npm install
```

#### Server

```bash
cd ../server
npm install
```

### 3. Start the development servers

#### Start the backend

```bash
cd server
npm run dev
```

#### Start the frontend

```bash
cd ../client
npm run dev
```

The client will typically run on [http://localhost:5173](http://localhost:5173) and the server on [http://localhost:3000](http://localhost:3000).

---

## 📂 Project Structure

```
CoEdit/
  client/    # Frontend (React, Vite, Tailwind, Monaco)
  server/    # Backend (Node.js, Express, Socket.IO)
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/AryanSONI00/CoEdit.git/issues) or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <b>Made with ❤️ for collaborative coding</b>
</p>
