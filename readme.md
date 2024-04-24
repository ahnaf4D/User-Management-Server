### User Management System - Backend

Welcome to the backend of the User Management System! This Node.js and Express.js server provides powerful functionalities to efficiently manage users, leveraging MongoDB as the database.

### Technologies Used

- **Node.js**: A JavaScript runtime environment.
- **Express.js**: A minimalist web application framework for Node.js.
- **MongoDB**: A flexible and scalable NoSQL database for storing user information.
- **dotenv**: A module for loading environment variables from a `.env` file, ensuring secure configuration.

### Frontend

For the frontend code of the User Management System, please refer to the [Client Side Code](https://github.com/ahnaf4D/User-Management-Client) repository.

### Quick Start

To quickly get started with the backend server:

1. Clone the repository containing this code.
2. Create a `.env` file in the root directory with the following variables:
   ```plaintext
   PORT=5000
   USER_NAME=your_mongodb_username
   USER_PASS=your_mongodb_password
   ```
3. Install dependencies using `npm install`.
4. Run the server using `npm start`.

### API Endpoints

- **GET /**: Root endpoint to verify server connectivity.
- **GET /users**: Retrieve a list of all users.
- **GET /users/:id**: Retrieve a specific user by ID.
- **POST /add-users**: Add a new user.
- **DELETE /users/:id**: Delete a user by ID.
- **PUT /update/:id**: Update a user by ID.

### Usage

- Upon starting the server, it will be accessible at `http://localhost:5000`.
- Utilize API testing tools like Postman or curl to interact with the server endpoints efficiently.
