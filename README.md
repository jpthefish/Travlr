# Travlr

## Overview

This is a web-based travel booking platform where users can search, view, and book travel experiences. The application comprises two main components: a customer-facing site powered by Express.js and an admin-facing site using Angular. This full-stack application is built on the MEAN stack, leveraging MongoDB as the database, Express.js as the backend server, Angular as the frontend, and Node.js as the runtime environment.

The application provides a RESTful API to perform CRUD operations on travel packages and user management. An extra layer of security is added to the admin-facing site through a secure login system to protect sensitive data and operations.

## Features

* Customer Site: Allows customers to search, view, and book travel packages.
* Admin Site: Provides functionality to manage travel packages, view bookings, and manage users.
* RESTful API: Offers a set of endpoints for interacting with the underlying MongoDB database.
* Security: Implements a secure login system on the admin site, using hashed passwords and JWT for session management

## Prerequisites

* Node.js v12 or later
* MongoDB v4.4 or later
* Angular CLI v6 or later

## Getting Started

1. Clone the repository to your local machine 
2. Navigate to the project directory ‘cd Travlr’
3. Install dependencies (For Express server:  cd app_server && npm install. For Angular client:  cd app_admin && npm install)

## Running the application

1. Start the Express server ( Navigate to the Travlr directory and start the server:  npm start.  By default, the server runs on http://localhost:3000)
4. Start the Angular client ( In a new terminal, navigate to the app_admin directory and start the Angular app:  ng serve.  By default, the client runs on http://localhost:4200)

## Security

Sensitive operations and data in the admin site are protected with a login system. Passwords are hashed using crypto and JSON Web Tokens (JWT) are used for managing sessions.

**Authors and Acknowledgment**

This project was created by J.P. Haynes and implements the requirements from Travlr Getaways’ specifications documentation. Documentation of the requirements, API endpoints, and other design specifications is available in the ‘docs’ directory.
