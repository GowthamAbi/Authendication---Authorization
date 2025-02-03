# User Authentication and Authorization with Bearer Token

This project implements user authentication and authorization using Bearer tokens in a Node.js application with Express.js, Mongoose, and JWT.

## Features
- User registration with hashed passwords.
- User login with JWT token generation.
- Protected routes using JWT verification middleware.

## Installation
1. Clone the repository.
2. Install dependencies: `npm install`.
3. Set up `.env` file with appropriate values.
4. Start the server: `npm run dev`.

## API Endpoints
1. **POST** `/api/auth/register` - Register a new user.
2. **POST** `/api/auth/login` - Login a user and retrieve a JWT.
3. **GET** `/api/auth/user` - Get user details (protected route).

## Deployment
Deployed on [Render](https://render.com/).

## Tools Used
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Postman for API testing

