### Hi there 👋

I'm Roy Bae, a Software Engineer based in Los Angeles, California. I'm passionate about building applications and solving technical challenges. With experience in full-stack development and digital marketing, I enjoy creating dynamic and user-friendly software products.

---

### Skills

* **Languages**: JavaScript, TypeScript, Python, Java, SQL, Go (Golang), Swift
* **Frameworks**: React, React Native, Node.js, Express.js, MongoDB
* **Tools & Platforms**: AWS, Git, Docker, Kubernetes, Jest, Jira, Bash, WordPress
* **Other**: SEO, Hotspot Tracking, Data Analysis

---

### Featured Project

#### Real-Time Tic-Tac-Toe

This project is a functional, real-time, two-player Tic-Tac-Toe game.

🔗 **Live Demo:** https://iridescent-bublanina-965e58.netlify.app/

**Project Overview**
This application allows users to create or join a room and play against each other. The game state is synchronized in real-time, and the interface displays the game grid, player information, and the current game status.

**Technical Highlights**
The core of this project is a real-time, bidirectional communication between the client and server using **Socket.IO**.

* **Server-Side**: The server, built with **Node.js** and **Express**, manages game rooms and player connections. It listens for events from clients (e.g., `createRoom`, `joinRoom`, `xMove`, `oMove`, `reset`) and emits messages to specific clients or all clients in a room.
* **Client-Side**: The front-end is a **React** application built with **Vite**. It connects to the Socket.IO server to send and receive game data. The socket instance is provided to all child components using a React Context, making it easily accessible without "prop drilling".

---

### Get In Touch

You can find me on GitHub or connect with me via email.

<p align="left">
<a href="mailto:RoyBae.dev@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
<a href="https://github.com/your-username-here"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>
