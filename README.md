# E-commerceApp-Node

E-commerceApp-Node is a full-stack web application built with Node.js, Express, MongoDB, and EJS. It provides a platform for managing products, user authentication, shopping cart functionality, and more.

## Features

- User authentication (signup, login, logout)
- Product management (CRUD operations)
- Shopping cart functionality
- Password reset via email
- Image upload for products
- Error handling and validation
- Responsive design using Bootstrap

## Technologies Used

- **Node.js**: Server-side JavaScript runtime environment.
- **Express**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing application data.
- **EJS**: Embedded JavaScript templates for rendering server-side views.
- **bcrypt.js**: Library for hashing passwords.
- **Multer**: Middleware for handling file uploads.
- **Nodemailer**: Module for sending emails.
- **Bootstrap**: Front-end component library for responsive design.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Rohit-ns5/e-commerceApp-node.git

2. Install dependencies:
    cd e-commerceApp-node
    npm install

3. Set up MongoDB:
    Create a MongoDB Atlas account (or use a local MongoDB instance).
    Replace MONGODB_URI in app.js with your MongoDB connection string. 

4. Set up SendGrid:
    Create a SendGrid account and generate an API key.
    Replace the api_key in controllers/auth.js with your SendGrid API key. 

5. Start the server:
    npm start

