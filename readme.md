# Task Management REST API
Demo Youtube video link: 
This project implements a RESTful API for managing tasks using Node.js, Express, and MongoDB with Mongoose.

## Features

- **CRUD Operations**: Allows creating, reading, updating, and deleting tasks.
- **MongoDB Integration**: Uses Mongoose to interact with a MongoDB database.
- **Error Handling**: Implements basic error handling for database operations.
- **Middleware**: Includes `body-parser` for parsing JSON and `cors` for handling Cross-Origin Resource Sharing.
- **Routing**: Defines routes for `/api/tasks` to manage tasks.

## Prerequisites

Before running the application, make sure you have the following installed:

- Node.js
- MongoDB

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SubasishMula2001/Task-manager
   cd Task-manager
   ```

2. **Install dependencies:**

   ```bash
   install dependencies in both file (frontend and backend)
   npm install
   ```

3. **Set up MongoDB:**

- Make sure to add mongdb atlas url and database name .

4. **Start the server:**

   ```bash
   npm start (in both file)
   like :
   in frontend folder - npm start
   and in backend folder - npm start
   ```

The server will start running on http://localhost:3000.

# API Endpoints

## Get all tasks

- **URL:** `/api/tasks`
- **Method:** `GET`
- **Response:** Retrieves all tasks stored in the database.

## Get a single task

- **URL:** `/api/tasks/:id`
- **Method:** `GET`
- **Response:** Retrieves a single task by its ID.

## Create a task

- **URL:** `/api/tasks`
- **Method:** `POST`
- **Request Body:** JSON object with `title`, `description`, and `dueDate` fields.
- **Response:** Creates a new task and returns the created task object.

## Update a task

- **URL:** `/api/tasks/:id`
- **Method:** `PUT`
- **Request Body:** JSON object with updated `title`, `description`, and `dueDate` fields.
- **Response:** Updates an existing task and returns the updated task object.

## Delete a task

- **URL:** `/api/tasks/:id`
- **Method:** `DELETE`
- **Response:** Deletes a task by its ID and returns a success message.

# Screenshots

![Task List Screenshot] ![Screenshot (2456)](https://github.com/SubasishMula2001/Task-manager/assets/74977100/52984df5-5dba-4f31-9da6-1cfde488181c)

![Task Detail Screenshot] ![Screenshot (2457)](https://github.com/SubasishMula2001/Task-manager/assets/74977100/3ea1dc55-6554-4fcf-ab42-db361f0e8992)


Developed By [Subasish Mula](https://subasishmula.me/).
