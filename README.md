# Express.js Todo App with Passport Middleware and SQLite

This is a simple todo application built using Express.js, Passport middleware, and SQLite as the backend database.

## Features

- User authentication using Passport middleware
- Create, read, update, and delete todos
- Mark todos as completed
- User-specific todos
- SQLite database for data storage

## Prerequisites

Make sure you have the following installed before running the application:

- Node.js and npm
- SQLite database

## Installation

1. Clone the repository:
git clone https://github.com/your-username/todo-app.git
2. Navigate to the project directory:
cd todo-app
3. Install the dependencies:
npm install
4. Create a  `.env`  file in the project root directory and provide the necessary environment variables:
PORT=3000
   SESSION_SECRET=your_session_secret
5. Create the SQLite database file:
touch database.sqlite
6. Run the database migrations to set up the necessary tables:
npx sequelize-cli db:migrate
## Usage

1. Start the application:
npm start
2. Open your web browser and navigate to  `http://localhost:3000` .

3. Register a new user or login with an existing account.

4. You can now create, view, update, and delete todos.

## Technologies Used

- Express.js: Fast, unopinionated, minimalist web framework for Node.js.
- Passport: Authentication middleware for Node.js.
- SQLite: Self-contained, serverless, and zero-configuration database engine.
- Sequelize: Promise-based ORM for Node.js, used for database management.

## License

[The Unlicense](https://opensource.org/licenses/unlicense)

## Credit
### Frontend
Created by [Jared Hanson](https://www.jaredhanson.me/)  
### Backend
Modified and completed by [Sxamoecode](https://github.com/Sxamoecode)
