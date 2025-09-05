<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hey! Nice to see you.</h1>

<p>Welcome to my page! </br> I'm <b>Anwar Marof</b>, a <b>Backend Developer</b> from <img src="https://cdn-icons-png.flaticon.com/512/197/197600.png" width="13"/> <b>Egypt</b>.</p>

<p>مرحبًا! أنا <b>أنور معروف</b> مطوّر Backend متخصص في <b>Node.js</b> و<b>Express</b> و<b>MongoDB</b>، أبني <b>REST APIs</b> نظيفة وآمنة، وأستخدم <b>React</b> لبناء واجهات تفاعلية، بالإضافة إلى <b>HTML</b> و<b>CSS</b> و<b>JavaScript</b> و<b>Socket.IO</b> للتواصل اللحظي.</p>

<h3>🛠️ Things I code with</h3>
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

<h3>📌 About me</h3>
<ul>
  <li>🔭 I build secure, well-documented <b>REST APIs</b> with <b>JWT auth</b>, <b>role-based access</b>, and clean architecture.</li>
  <li>🗄️ Experienced with <b>Mongoose</b>, <b>MongoDB Atlas</b>, pagination, and aggregation pipelines.</li>
  <li>🧪 I test endpoints using <b>Postman</b> and write reusable middlewares & validators.</li>
  <li>⚙️ Focused on writing clean, scalable backend services.</li>
  <li>💬 I also use <b>Socket.IO</b> for real-time communication (chat apps, notifications, live updates).</li>
  <li>🌱 Currently learning <b>Docker</b> & <b>CI/CD</b>.</li>
</ul>

---

<h3>🚀 Highlighted projects</h3>
<table>
  <thead align="center">
    <tr>
      <td><b>🎁 Project</b></td>
      <td><b>⚙️ Stack</b></td>
      <td><b>🧩 Features</b></td>
      <td><b>🔗 Link</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Task Manager API</b></td>
      <td>Node.js, Express, MongoDB, JWT</td>
      <td>Auth, CRUD, Validation, Pagination</td>
      <td><a href="https://github.com/anwar-dev55/Task-Manager">Repo</a></td>
    </tr>
    <tr>
      <td><b>Book Management with Authentication</b></td>
      <td>Node.js, Express, MongoDB, React</td>
      <td>User Auth, Protected Routes, CRUD</td>
      <td><a href="https://github.com/anwar-dev55/Book-mangement-with-authentication">Repo</a></td>
    </tr>
    <tr>
      <td><b>Chat App (Beginner)</b></td>
      <td>Node.js, Socket.IO, MongoDB</td>
      <td>Real-time messaging, JWT, Rooms</td>
      <td><a href="https://github.com/anwar-dev55/Chatting-app">Repo</a></td>
    </tr>
  </tbody>
</table>

---

<h3>🧑‍💻 Code samples</h3>

```js
// Example: Express error handler (centralized)
app.use((err, req, res, next) => {
  const status = err.status || 500;
  const message = err.message || 'Internal Server Error';
  res.status(status).json({ success: false, message });
});

// Example: Socket.IO error handling
io.on('connection', (socket) => {
  console.log('✅ New client connected');

  socket.on('error', (err) => {
    console.error('❌ Socket.IO Error:', err.message);
    socket.emit('errorMessage', { success: false, message: err.message });
  });

  socket.on('disconnect', () => {
    console.log('⚡ Client disconnected');
  });
});

