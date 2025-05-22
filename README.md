# LessonBookingSystem - Backend (Express.js-App)

## Overview
Backend API for the LessonBookingSystem full-stack app, built with Express.js and Node.js. Manages user authentication, lesson scheduling, and booking operations.

## Features
- RESTful API endpoints for users, lessons, and bookings
- Role-based access control (student/instructor)
- JWT authentication and authorization
- Data validation and error handling
- MongoDB database integration with Mongoose

## Technologies
- Node.js, Express.js
- MongoDB, Mongoose
- JSON Web Tokens (JWT)
- bcrypt for password hashing
- dotenv for environment variables

## Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/LessonBookingSystem-Express-Backend.git
   cd LessonBookingSystem-Express-Backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
4. Create a .env file with your environment variables:
   ```bash
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/lesson-booking
   JWT_SECRET=your_jwt_secret_key
   ```
5. Start the server:
   ```bash
   npm start
   ```
6. API runs on http://localhost:5000

## Notes
- Implements REST API endpoints for user registration, login, lessons, and bookings.  
- Uses JWT tokens to protect routes and enforce role-based permissions.  
- Passwords are securely hashed with bcrypt before storing in MongoDB.  
- Mongoose schemas define the data models and relationships.  
- Includes comprehensive error handling and input validation.  
- Supports CORS for frontend integration.  
