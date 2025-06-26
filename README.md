# LearnX

**LearnX** is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js).
The project offers a modern, dynamic platform for learning modules, with a robust backend and responsive frontend.

## Features

- User Authentication: Secure registration and login with hashed tokens (sha256)
- Dynamic Course Content: Browse, view, and interact with different modules
- Responsive UI: Modern design, works across devices
- RESTful API: Backend manages users and courses, interacts via HTTP requests from the frontend
- MERN Architecture: Clean separation between backend (API/server) and frontend (React UI)

## Technologies Used

Frontend:
- React.js
- Tailwind CSS
- Fetch API (for HTTP requests)

Backend:
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- sha256 (for hashing/tokenization)
- CORS

## Getting Started

Prerequisites:
- Node.js
- MongoDB

Clone the Repository:
```
git clone https://github.com/PanavMhatre/LearnXWEb.git
cd LearnXWEb
```
Backend Setup:
```
cd backend
npm install
```
(Optional) Add a .env file if needed (see .env.example)
```
npm start
```
Frontend Setup (open a new terminal window/tab):
```
cd frontend
npm install
npm start
```

Open the App:
Open your browser and go to: http://localhost:3000

## Contributing

Feel free to open issues or submit pull requests!

## License

MIT License

Made with ❤️ by Panav Mhatre
