# Server

This is the backend API for the EdTech platform built with Node.js and Express.

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Create a `.env` file with your environment variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/edtech-platform
   JWT_SECRET=your_jwt_secret_here
   ```

3. Start the development server:
   ```
   npm run dev
   ```

## API Features

- User authentication and authorization
- Course CRUD operations
- Student enrollment management
- Progress tracking
- File upload handling
