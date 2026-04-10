# websocket-chat-app

# 💬 Real-Time Chat App (WebSocket + Node.js)

## 🚀 Overview

This project is a **real-time chat application** built using **Node.js, Express, and WebSockets (`ws`)**.

It demonstrates **full-duplex communication**, allowing clients to send and receive messages instantly without refreshing the page.

---

## ✨ Features

* ⚡ Real-time messaging using WebSockets
* 👥 Multi-client support (broadcast messages)
* 🌐 Simple and clean frontend UI
* 🔄 Event-driven backend architecture

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Real-time Communication:** WebSocket (`ws`)
* **Frontend:** HTML, CSS, JavaScript

---

## 📁 Project Structure

```
realtime-chat-app/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── index.js
├── package.json
├── README.md
└── screenshots/
```

---

## ⚙️ Setup & Run

### 1️⃣ Install dependencies

```
npm install
```

### 2️⃣ Run server

```
npm start
```

### 3️⃣ Open in browser

```
http://localhost:8080
```

---

## 🔌 How It Works

1. Express creates an HTTP server
2. WebSocket server is attached to the same server
3. Clients connect using `ws://localhost:8080`
4. When a message is sent:

   * Server receives it
   * Server broadcasts it to all connected clients
5. All users see messages instantly

---

## 🧠 Key Concepts Learned

* WebSocket protocol (persistent connection)
* Event-driven programming
* Real-time communication systems
* Client-server architecture

---

## 🔮 Future Improvements

* 👤 Add usernames & timestamps
* 🔔 Real-time notifications (e.g., visa slot alerts)
* 💾 Store chat history (MongoDB)
* ☁️ Deploy to cloud (Render / Railway)

---

## 👨‍💻 Author

**Kenil Maniya**

---

## ⭐ Show Your Support

If you like this project, feel free to ⭐ star the repo!
