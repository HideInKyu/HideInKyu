### About Me

Hello! My name is Roy Bae. I am a Software Engineer based in Los Angeles, California. I am currently a Computer Science student at El Camino College and have experience in a variety of software engineering roles, including developing digital presentations, and building business applications. My past work has included analyzing sales data and leveraging digital marketing campaigns to increase revenue and foot traffic.

### Skills

* **Languages**: Python, JavaScript, TypeScript, Java, SQL, Go (Golang), Swift
* **Frameworks**: React, React Native, Node.js, Express.js, MongoDB
* **Tools & Platforms**: AWS, Git, Docker, Kubernetes, Jest, Jira, Bash, WordPress
* **Other**: SEO, Hotspot Tracking, Data Analysis

### Projects

#### Real-Time Tic-Tac-Toe

This project is a functional, real-time, two-player Tic-Tac-Toe game.

**Live Demo:** [https://iridescent-bublanina-965e58.netlify.app/](https://iridescent-bublanina-965e58.netlify.app/)

**Project Overview**
This application allows users to create or join rooms to play against each other. The game state synchronizes in real-time between the two players, and the interface displays the game grid, player information, and game status.

**Technical Highlights**
This project demonstrates the implementation of real-time, bidirectional communication between a client and a server using Socket.IO.

* **Server-Side**: The server, built with Node.js and Express, manages game rooms and player connections. It listens for events from clients (e.g., `createRoom`, `joinRoom`, `xMove`, `oMove`, `reset`) and sends messages to specific clients or all clients in a room.
* **Client-Side**: The front-end is a React application built with Vite. It connects to the Socket.IO server to send and receive game data. The socket instance is provided to all child components through a React Context, making it easily accessible. Event handling is managed within a useEffect hook in the `Grid.jsx` component.