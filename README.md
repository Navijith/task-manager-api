# Task Manager REST API

## Overview

A RESTful API built using Node.js, Express.js, and MongoDB that performs CRUD operations for task management.

## Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* Postman

## Features

* Create a Task
* Get All Tasks
* Get Task by ID
* Update Task
* Delete Task

## Installation

```bash
npm install
npm run dev
```

## Environment Variables

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

## API Endpoints

### Create Task

POST /api/tasks

### Get All Tasks

GET /api/tasks

### Get Task By ID

GET /api/tasks/:id

### Update Task

PUT /api/tasks/:id

### Delete Task

DELETE /api/tasks/:id

## Author

Navijith
