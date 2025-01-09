# Second-Hand Marketplace

## Project Overview

The Second-Hand Marketplace is a web-based platform that allows users to buy and sell used items. Built with the MEAN stack (MongoDB, Express.js, Angular, Node.js), it aims to provide a user-friendly and secure environment for second-hand transactions.

## Features

- **User Registration and Login**: Secure authentication with JSON Web Tokens (JWT).
- **Product Listings**: Create, edit, delete, and browse product listings with images, descriptions, and categories.
- **Search and Filters**: Advanced search and filters by price, category, and location.
- **Real-Time Chat**: Secure communication for negotiations.
- **Admin Panel**: Manage users and listings, monitor inappropriate content.
- **Responsive Design**: Optimized for all device types.
- **Optional Payment Integration**: Secure transactions via payment gateways.

## Technology Stack

- **Frontend**: Angular with Angular Material for UI components.
- **Backend**: Node.js and Express.js.
- **Database**: MongoDB with Mongoose ORM.
- **Authentication**: JWT for secure sessions.
- **Real-Time Communication**: Socket.IO for chat and notifications.

### How to use this file:
1. Copy the content of the `README.md` file.
2. Create a new file named `README.md` in the root directory of your GitHub repository.
3. Paste the content into the `README.md` file.
4. Commit and push the file to your GitHub repository.


### Contributors

- Mohit Kumar Saini
- Rahul Kumar Rajak 
- Satyam Kumar 
- Harish Choudhary
- Ukirde Jaydeep Shivaji 
   
## Installation Guide

```bash
# Clone the repository
git clone https://github.com/your-repo/second-hand-marketplace.git

# Navigate to the project directory
cd second-hand-marketplace

# Install backend dependencies
npm install

# Navigate to the client directory and install frontend dependencies
cd client
npm install

# Configure environment variables for backend and frontend

# Start the development servers

# Backend server
npm start

# Frontend server
cd client
ng serve

# Open the application in a browser at http://localhost:4200

# Authentication
POST /api/auth/register      # Register a new user
POST /api/auth/login         # Login user and issue JWT

# Product Listings
GET /api/products            # Fetch all products
POST /api/products           # Create a new product (authenticated users)
PUT /api/products/:id        # Update product details (authenticated users)
DELETE /api/products/:id     # Delete a product (authenticated users)

# Chat
GET /api/chat/:conversationId # Fetch chat history
POST /api/chat               # Send a message




