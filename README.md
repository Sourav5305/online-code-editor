Code - Real-Time Collaborative Code Editor
A web-based platform allowing multiple users to write, edit, and run code together in real-time. This project demonstrates the power of WebSockets for creating seamless, low-latency collaborative applications.

Key Features

Real-Time Collaboration: Synchronized code editing for multiple users in the same session using Socket.io.

Multi-Room Architecture: Create unique, private coding rooms that users can join via a shared ID.

Rich Code Editor: Integrated with the Monaco Editor (the engine behind VS Code) for a professional coding experience.

Syntax Highlighting: Supports syntax highlighting for popular languages like JavaScript, Python, and C++.

Shared Terminal: A shared output panel to display the results of code execution for all users in the room.

🛠️ Tech Stack
Frontend: React.js, Socket.io-client

Backend: Node.js, Express.js

Real-Time Engine: WebSockets (Socket.io)

Code Editor: Monaco Editor

⚙️ Setup and Installation
To run this project locally, follow these steps:

Clone the repository:

git clone [your-repo-link]
cd EchoCode

Install server dependencies:

cd server
npm install

Install client dependencies:

cd ../client
npm install

Run the development servers:
You'll need two separate terminals for this.

In the /server directory, run:

npm start

In the /client directory, run:

npm start

Open your browser and navigate to http://localhost:3000 to see the application in action.
