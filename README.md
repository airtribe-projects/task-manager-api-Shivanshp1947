# Task Manager Backend API

A robust RESTful API built with Node.js and Express for managing tasks. This project was developed as part of the Airtribe Backend Engineering Launchpad.

## 🚀 Features
- **CRUD Operations**: Create, Read, Update, and Delete tasks.
- **Data Persistence**: Tasks are stored in a local `task.json` file.
- **Input Validation**: Ensures task data is complete before saving.
- **Testing**: Includes a comprehensive test suite using Jest/Supertest.

## 📁 Project Structure
```text
.
├── routes/
│   └── route.js       # API route definitions
├── test/
│   └── server.test.js # Test files
├── app.js             # Main entry point (Express server setup)
├── task.json          # JSON database for storing tasks
├── package.json       # Project metadata and scripts
├── .gitignore         # Git ignore rules
└── README.md          # Project documentation

🚦 API Endpoints
Method,Endpoint,Description
GET,/tasks,Retrieve all tasks
GET,/tasks/:id,Retrieve a specific task by ID
POST,/tasks,Create a new task
PUT,/tasks/:id,Update an existing task
DELETE,/tasks/:id,Delete a task

