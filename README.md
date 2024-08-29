#Authentication
#Overview
The authentication system in the Task Manager Application is designed to securely manage user access to the application. It supports traditional email/password registration and login, as well as Google OAuth for simplified login.

Features
User Registration: Users can sign up with their email and password.
User Login: Existing users can log in using their registered credentials.
Google OAuth: Users can log in using their Google account for quicker access.
Token-Based Authentication: JSON Web Tokens (JWT) are used to maintain secure sessions.
Protected Routes: Only authenticated users can access certain parts of the application.
Session Management: Users stay logged in across sessions until they log out.

Technologies Used
Node.js with Express.js for the backend.
Passport.js for managing authentication strategies.
JWT (JSON Web Token) for secure session management.
bcrypt for hashing passwords before storing them in the database.
Google OAuth 2.0 for third-party login integration.
