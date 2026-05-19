<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hey! Nice to see you.</h1>

<p>Welcome to my page! </br> I'm <b>Anwar Marof</b>, a <b>Backend Developer</b> from <img src="https://cdn-icons-png.flaticon.com/512/197/197600.png" width="13"/> <b>Egypt</b>.</p>

<p>Hello! I'm <b>Anwar Marof</b>, a Backend Developer specialized in <b>Node.js</b>, <b>Express</b>, and <b>MongoDB</b>. I build clean and secure <b>REST APIs</b>, and I also use <b>React</b> to create interactive user interfaces, along with <b>HTML</b>, <b>CSS</b>, <b>JavaScript</b>, and <b>Socket.IO</b> for real-time communication.</p>

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
  <li>🔭 I build secure, well-documented <b>REST APIs</b> with <b>JWT authentication</b>, <b>role-based access control</b>, and clean architecture.</li>
  <li>🗄️ Experienced with <b>Mongoose</b>, <b>MongoDB Atlas</b>, pagination, and aggregation pipelines.</li>
  <li>🧪 I test endpoints using <b>Postman</b> and create reusable middlewares and validators.</li>
  <li>⚙️ Focused on building clean, scalable, and maintainable backend services.</li>
  <li>💬 I use <b>Socket.IO</b> for real-time applications such as chat apps, notifications, and live updates.</li>
  <li>🌱 Currently learning <b>Docker</b> and <b>CI/CD</b>.</li>
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
      <td><b>LiveScore App</b></td>
      <td>Node.js, Express, Socket.IO, MongoDB</td>
      <td>Live Match Updates, Real-time Notifications, Authentication</td>
      <td><a href="#">Repo</a></td>
    </tr>

    <tr>
      <td><b>Studify</b></td>
      <td>Node.js, Express, MongoDB, React</td>
      <td>Course Management, Authentication, Student Dashboard</td>
      <td><a href="#">Repo</a></td>
    </tr>

    <tr>
      <td><b>E-Learning System</b></td>
      <td>Node.js, Express, MongoDB, React</td>
      <td>Instructor & Student Roles, Video Lessons, Progress Tracking</td>
      <td><a href="#">Repo</a></td>
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
