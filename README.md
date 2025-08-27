<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> Hey! Nice to see you.</h1>

<p>Welcome to my page! </br> I'm <b>Anwar Marof</b>, a <b>Backend Developer</b> from <img src="https://cdn-icons-png.flaticon.com/512/197/197600.png" width="13"/> <b>Egypt</b>.</p>

<p>مرحبًا! أنا <b>أنور معروف</b> مطوّر Backend متخصص في <b>Node.js</b> و<b>Express</b> و<b>MongoDB</b>، أبني <b>REST APIs</b> نظيفة وآمنة، وأستخدم <b>React</b> لبناء واجهات تفاعلية، بالإضافة إلى <b>HTML</b> و<b>CSS</b> و<b>JavaScript</b>.</p>

<h3>🛠️ Things I code with</h3>
<p>
  <img alt="Nodejs" src="https://img.shields.io/badge/-Node.js-43853d?style=flat-square&logo=node.js&logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="Mongoose" src="https://img.shields.io/badge/-Mongoose-880000?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="REST API" src="https://img.shields.io/badge/-REST%20API-0A66C2?style=flat-square" />
  <img alt="JWT" src="https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img alt="Postman" src="https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
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
      <td>Node.js, Socket.io, MongoDB</td>
      <td>Real-time messaging, JWT, Rooms</td>
      <td><i>Coming soon...</i></td>
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
```

```js
// Example: Auth middleware (JWT)
const jwt = require('jsonwebtoken');
module.exports = function auth(req, res, next) {
  const token = req.headers.authorization?.split(' ')[1];
  if (!token) return res.status(401).json({ message: 'No token provided' });
  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch {
    return res.status(401).json({ message: 'Invalid token' });
  }
};
```

```js
// Example: Task schema (Mongoose)
const mongoose = require('mongoose');
const taskSchema = new mongoose.Schema(
  {
    title: { type: String, required: true, trim: true },
    description: { type: String, default: '' },
    status: { type: String, enum: ['pending', 'in-progress', 'done'], default: 'pending' },
    owner: { type: mongoose.Schema.Types.ObjectId, ref: 'User', required: true },
  },
  { timestamps: true }
);
module.exports = mongoose.model('Task', taskSchema);
```

---

<h3>🏆 Certs & Achievements</h3>
<ul>
  <li>Built multiple REST APIs with JWT and robust middleware (validation, rate limiting, CORS).</li>
  <li>Experience structuring production-ready Node/Express projects.</li>
  <li>Active on GitHub sharing open-source backend projects.</li>
</ul>

---

<h3>📫 Where to find me</h3>
<p>
  <a href="https://github.com/anwar-dev55" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/anwar-marof-68518b323/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anwar.dev55@gmail.com" target="_blank"><img alt="Email" src="https://img.shields.io/badge/Email-333333?&style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

<p align="center">This README is handcrafted by <b>Anwar Marof</b> — Backend Developer (Node.js • Express • MongoDB • REST APIs)</p>
