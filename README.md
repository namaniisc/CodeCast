#  CodeCast - Real-time Code Collaboration

A real-time collaborative code editor where multiple users can join a room and code together live. Built from scratch using React.js, Socket.io, Express.js, and Bootstrap.

## Demo

![Demo](demo.gif)

How it works:
1. Enter your name and click “Create New Room” or enter a Room ID to join.
2. Share the Room ID/URL with others.
3. Collaborate live – any code you type will sync instantly.
4. Get real-time updates when people join or leave.

## Technologies

Frontend:
- React.js  
- Bootstrap  
- CodeMirror (code editor)  
- React Router  
- UUID (for unique room IDs)  
- react-avatar (user avatars)  

Backend:
- Node.js  
- Express.js  
- Socket.io (real-time WebSocket communication)

## Features

- Create & Join Rooms  
- Real-Time Code Sync Across Users  
- Unique Room URLs with Shareable Links  
- Username & Avatar Display  
- Toast Notifications for Join/Leave  
- Room Clean-up and Disconnect Handling



## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/namaniisc/CodeCast.git
   cd CodeCast
   ```

2. Install client dependencies:
   ```bash
   cd client
   npm install
   ```

3. Install server dependencies:
   ```bash
   cd ../server
   npm install
   ```

## Running the App

1. Start the backend:
   ```bash
   cd server
   npm start
   ```

2. Start the frontend:
   ```bash
   cd ../client
   npm start
   ```

3. Open in browser:
   ```
   http://localhost:3000
   ```

## Project Structure

```
.
├── client/             React frontend
│   ├── public/         Static assets (e.g., logo)
│   └── src/            Source code
│       ├── components/
│       ├── pages/
│       └── App.js
├── server/             Express + Socket.io backend
│   ├── index.js
│   └── package.json
└── README.md
```

## Contributing

Pull requests and issues are welcome! Feel free to improve features, fix bugs, or enhance the documentation.
