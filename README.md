# <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hey! Nice to see you.

Welcome to my page!  
I'm **Anwar Marof**, a **Backend Developer** from <img src="https://cdn-icons-png.flaticon.com/512/197/197600.png" width="13"/> **Egypt**.

Hello! I'm **Anwar Marof**, a Backend Developer specialized in **Node.js**, **Express**, and **MongoDB**. I build clean and secure **REST APIs**, and I also use **React** to create interactive user interfaces, along with **HTML**, **CSS**, **JavaScript**, and **Socket.IO** for real-time communication.

---

## 🛠️ Things I code with

<p>
  <img alt="Nodejs" src="https://img.shields.io/badge/-Node.js-43853d?style=flat-square&logo=node.js&logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="Mongoose" src="https://img.shields.io/badge/-Mongoose-880000?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="REST API" src="https://img.shields.io/badge/-REST%20API-0A66C2?style=flat-square" />
  <img alt="JWT" src="https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img alt="Postman" src="https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
  <img alt="Socket.IO" src="https://img.shields.io/badge/-Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000" />
  <img alt="HTML5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img alt="NPM" src="https://img.shields.io/badge/-NPM-CB3837?style=flat-square&logo=npm&logoColor=white" />
  <img alt="VSCode" src="https://img.shields.io/badge/-VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" />
</p>

---

## 📌 About me

- 🔭 I build secure, well-documented **REST APIs** with **JWT authentication**, **role-based access control**, and clean architecture.
- 🗄️ Experienced with **Mongoose**, **MongoDB Atlas**, pagination, and aggregation pipelines.
- 🧪 I test endpoints using **Postman** and create reusable middlewares and validators.
- ⚙️ Focused on building clean, scalable, and maintainable backend services.
- 💬 I use **Socket.IO** for real-time applications such as chat apps, notifications, and live updates.
- 🌱 Currently learning **Docker** and **CI/CD**.

---

## 🚀 Highlighted Projects

| 🎁 Project | ⚙️ Stack | 🧩 Features | 🔗 Link |
|---|---|---|---|
| **LiveScore App** | Node.js, Express, Socket.IO, MongoDB | Live Match Updates, Real-time Notifications, Authentication | [Repo](#) |
| **Studify** | Node.js, Express, MongoDB, React | Course Management, Authentication, Student Dashboard | [Repo](#) |
| **E-Learning System** | Node.js, Express, MongoDB, React | Instructor & Student Roles, Video Lessons, Progress Tracking | [Repo](#) |
| **Task Manager API** | Node.js, Express, MongoDB, JWT | Authentication, CRUD, Validation, Pagination | [Repo](https://github.com/anwar-dev55/Task-Manager) |
| **Book Management with Authentication** | Node.js, Express, MongoDB, React | User Authentication, Protected Routes, CRUD Operations | [Repo](https://github.com/anwar-dev55/Book-mangement-with-authentication) |
| **Chat App (Beginner)** | Node.js, Socket.IO, MongoDB | Real-time Messaging, JWT Authentication, Chat Rooms | [Repo](https://github.com/anwar-dev55/Chatting-app) |

---

## 🧑‍💻 Code Samples

```js
// Example: Express error handler (centralized)
app.use((err, req, res, next) => {
  const status = err.status || 500;
  const message = err.message || 'Internal Server Error';

  res.status(status).json({
    success: false,
    message
  });
});

// Example: Socket.IO error handling
io.on('connection', (socket) => {
  console.log('✅ New client connected');

  socket.on('error', (err) => {
    console.error('❌ Socket.IO Error:', err.message);

    socket.emit('errorMessage', {
      success: false,
      message: err.message
    });
  });

  socket.on('disconnect', () => {
    console.log('⚡ Client disconnected');
  });
});
```
