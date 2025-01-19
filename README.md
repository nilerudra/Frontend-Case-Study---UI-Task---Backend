# Backend for Add User Profile Application

This is the backend server for the **Add User Profile Application**, built with **Node.js** and **Express**. It handles API requests for adding, retrieving, and deleting user profiles. The data is stored in **MongoDB**.

## Features

- **Create User Profile**: Endpoint to add a new user profile.
- **Get User Profiles**: Endpoint to fetch all user profiles.
- **Delete User Profile**: Endpoint to delete a user profile by ID.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web framework for building the API.
- **MongoDB**: Database for storing user profiles.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB.
- **CORS**: Middleware for enabling Cross-Origin Request Sharing (CORS).

## Setup and Installation

To run the backend locally, follow these steps:

### 1. Clone the repository:
```
git clone <repository-url>
```

### 2. Navigate into the project directory:
```
cd <backend-directory>
```

### 3. Install dependencies:
```
npm install
```

### 4. Create .env file
Create a .env file in the root directory and add your MongoDB URI for connecting to the database. Example:
```
MONGO_URI=mongodb://localhost:27017/userProfiles
PORT=3000
```

### 5. Run the backend server:
```
node server.js
```
