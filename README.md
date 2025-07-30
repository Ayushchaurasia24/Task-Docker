📝 Task-Docker

A full-stack Todo application designed to help users manage their tasks efficiently. Built with a modern tech stack, this app allows users to create, read, update, and delete tasks seamlessly.

🚀 Features
*Task Management: Create, view, update, and delete tasks.

*User Authentication: Secure login and registration system.

*Responsive Design: Optimized for both desktop and mobile devices.

*RESTful API: Backend API built with Express.js.

*MongoDB Integration: Tasks and user data stored in MongoDB.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript, React
Backend: Node.js, Express.js
Database: MongoDB
Version Control: Git

📁 Project Structure
todoapp/
├── client/             # Frontend source code
├── controllers/        # Route handlers
├── middleware/         # Custom middleware functions
├── models/             # Mongoose schemas
├── routes/             # API route definitions
├── .env                # Environment variables
├── package.json        # Project metadata and dependencies
├── server.js           # Entry point of the application

⚙️ Installation
1 - Clone the repository:
git clone https://github.com/Ayushchaurasia24/todoapp.git
cd todoapp

2 - Install backend dependencies:
npm install

3 - Set up environment variables:
Create a .env file in the root directory and add the following:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4- Start the server:
npm start

5 - Navigate to the frontend:
cd client
Open index.html in your browser to view the application.

📦 API Endpoints
POST /api/auth/register - Register a new user

POST /api/auth/login - Login user

GET /api/tasks - Retrieve all tasks

POST /api/tasks - Create a new task

PUT /api/tasks/:id - Update a task

DELETE /api/tasks/:id - Delete a task

🧪 Testing
Instructions for running tests (if available) can be added here.

🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

📄 License
This project is licensed under the MIT License.
