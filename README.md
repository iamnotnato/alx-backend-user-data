## ALX Backend User Data

### Purpose

This project is a Node.js and MongoDB application that manages user data, providing a complete REST API for CRUD (Create, Read, Update, Delete) operations. It is designed for educational purposes to demonstrate fundamental backend development concepts.

### Features

* CRUD functionality for user profiles
* Secure user authentication and authorization
* Validation and error handling
* Unit testing

### Technologies Used

* Node.js (Express.js framework)
* MongoDB (mongoose ORM)
* JWT (JSON Web Tokens) for authentication
* bcrypt for password hashing
* Jest for unit testing

### Getting Started

Clone the repository, install dependencies, and run the server locally:

```bash
git clone https://github.com/iamnotnato/alx-backend-user-data.git
cd alx-backend-user-data
npm install
npm start
```

### Usage

To use the API, send the following requests:

```
GET /api/v1/users - Get all users
POST /api/v1/users - Create a new user
GET /api/v1/users/:id - Get a specific user by ID
PUT /api/v1/users/:id - Update a user by ID
DELETE /api/v1/users/:id - Delete a user by ID
```

### Authentication

Users must provide a valid JWT access token to access authenticated routes. To obtain a token, send a POST request to `/api/v1/auth/login` with the following JSON body:

```json
{
  "email": "user@example.com",
  "password": "password"
}
```

### Contribution Guidelines

Contributions to the project are welcome. Please follow these guidelines:

* Fork the repository and create a pull request.
* Write clear and concise commit messages.
* Add unit tests for any new functionality.

### License

This project is licensed under the MIT License.

### Contact

For any questions or support, please contact the maintainer through [GitHub](https://github.com/iamnotnato).
