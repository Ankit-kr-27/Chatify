Chatify
Overview

Chatify is a full-stack real-time chat application built with React for the frontend and Node.js + Express + Socket.IO for the backend. It enables users to join rooms and exchange instant messages with live updates, demonstrating core concepts of WebSockets and modern web development.

This README provides clear instructions for setup, usage, and development, suitable for contributors or end users.

Features

Real-time messaging using Socket.IO

User login (simple name/room join interface)

Persistent frontend and backend separation

Room-based chat (multiple distinct chat rooms)

Responsive UI built with React

Easy setup and local development

Specific feature details in your implementation (authentication, database support, message persistence, UI components) should be added if available.

Tech Stack
Layer	Technology
Frontend	React, Socket.IO-Client, CSS/HTML
Backend	Node.js, Express, Socket.IO
Real-time	WebSockets via Socket.IO
Deployment	Can be hosted on services like Render / Vercel (frontend/backend separately)
Demo (Optional)

If you have deployed versions of frontend and backend, include links here.

Getting Started
Prerequisites

Ensure you have the following installed:

Node.js (v14 or newer)

npm or yarn

(Optional) A hosting service for production

Installation
1. Clone the Repository
git clone https://github.com/Ankit-kr-27/Chatify.git
cd Chatify

2. Backend Setup
cd backend
npm install


Create a .env file with appropriate variables (if required), for example:

PORT=5000


Start the backend server:

npm run dev


The server should now be running on http://localhost:5000.

3. Frontend Setup
cd ../frontend
npm install


Configure any environment variables, if needed (REACT_APP_API_URL pointing to backend).

Start the React development server:

npm start


The app should now be running on http://localhost:3000.

How to Use

Open the frontend in your browser.

Enter your username and room name.

Join the room to send and receive real-time messages.

Open multiple tabs or browsers to simulate multiple users.

Project Structure
Chatify/
├── backend/           # Express + Socket.IO server
│   ├── index.js       # Main server entrypoint
│   ├── socket.js      # Socket handlers
│   └── package.json
├── frontend/          # React application
│   ├── src/
│   ├── public/
│   └── package.json
├── .gitignore
└── README.md


This structure reflects a typical full-stack chat app where frontend and backend are decoupled.

Contributing

Contributions are welcome. To contribute:

Fork the repository

Create a feature branch: git checkout -b feature/my-feature

Commit your changes: git commit -m "Add feature"

Push to your fork: git push origin feature/my-feature

Open a pull request describing your changes

License

This project is open source and available under the MIT License.
(Include a LICENSE file if you have one)

Acknowledgements

This project is inspired by common real-time chat applications using React and Socket.IO and similar repositories on GitHub that implement real-time communication patterns.