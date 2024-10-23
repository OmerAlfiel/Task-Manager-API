# Task-Manager-API
This project is a Task Manager API built with Node.js and Express. It provides a backend service for managing users and their tasks. The project structure is organized into several directories, each serving a specific purpose:

config/: Contains configuration files, such as the database connection setup in db.js.
controllers/: Houses the controller files, which contain the logic for handling requests. For example, taskController.js and userController.js manage task and user-related operations, respectively.
middlewares/: Includes middleware functions like authMiddleware.js for handling authentication.
models/: Defines the data models for the application, such as taskModel.js and userModel.js.
routes/: Contains route definitions that map HTTP requests to controller functions. For instance, taskRoutes.js and userRoutes.js define the routes for task and user operations.
The main application file, app.js, sets up the Express server, connects to the database, and configures middleware and routes. The server listens on a port specified in the environment variables or defaults to port 5000.

Key features of this API include:

User authentication and authorization.
CRUD operations for tasks.
Organized and modular code structure for scalability and maintainability.
To run the project, ensure you have Node.js installed, then install the dependencies using npm install and start the server with npm start. The API will be accessible at http://localhost:5000.

## Install necessary dependencies:
npm install express mongoose jsonwebtoken bcryptjs dotenv
npm install --save-dev nodemon
