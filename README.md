# Connectify

## Overview

Connectify is a Social Media Web Application that is designed to provide users with a platform to share their thoughts, interact with other users, and customize their user experience with features like dark mode. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js), this application ensures a robust and scalable solution for modern social networking.

## Features

- **User Authentication**: Secure login and registration system using JWT.
- **Post Creation and Management**: Users can create, edit, and delete posts.
- **Likes**: Users can like posts.
- **Dark Mode**: Toggle between light and dark themes.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JSON Web Tokens (JWT)

## Installation

### Prerequisites

- Node.js (v14 or higher)
- MongoDB

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/arnavdaryani/Connectify.git
   cd Connectify
   ```

2. Install dependencies for the backend
   ```bash
   cd server
   npm install
   ```

3. Install dependencies for the frontend
   ```bash
   cd ../client
   npm install
   ```

4. Set up environment variables
   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. Run the application
   ```bash
   cd backend
   npm start

   cd ../frontend
   npm start
   ```
