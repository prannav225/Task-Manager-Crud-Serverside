# Task-Manager-Crud-Serverside

This is the server-side component of the Todo CRUD (Create, Read, Update, Delete) application. It provides the backend API for managing to-do items. The server is built using Node.js, Express, and MongoDB.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)

## Features

- Create new to-do items with a title and description.
- Read the list of existing to-do items.
- Update to-do items by editing their titles and descriptions.
- Delete to-do items.
- Prevents the creation of duplicate tasks.

## Technologies Used

- **Node.js:** A JavaScript runtime used for building the server.
- **Express:** A web application framework for Node.js.
- **MongoDB:** A NoSQL database for storing to-do item data.
- **Mongoose:** An ODM (Object Data Modeling) library for MongoDB.
- **Body-parser:** Middleware for parsing HTTP request bodies.
- **CORS:** Middleware for enabling cross-origin resource sharing.
- **dotenv:** Used for environment variable management.

## Getting Started

1. Clone this repository to your local machine.

2. Install dependencies using the following command:
   ```bash
   npm install
   
3. Create a .env file in the root directory of the project and set the following environment variables:
   PORT=5001
   MONGODB_URI=mongodb://localhost:27017/todo-crud
   
5. Start the server with the following command:
   ```bash
   node server
The server will run on port 5001 by default. You can change the port in the .env file.


## API Endpoints
- POST /todos: Create a new to-do item.
- GET /todos: Retrieve all to-do items.
- PUT /todos/:id: Update a to-do item by ID.
- DELETE /todos/:id: Delete a to-do item by ID.

  
## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them.
- Push your changes to your forked repository.
- Submit a pull request to the main repository.

## Author 
**Pranav M**
   
