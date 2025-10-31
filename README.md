# Task Manager - Token & Cookie Authentication

This is a simple Task Management app built using Node.js and Express.  
It uses **JWT tokens stored in HTTP-only cookies** for secure authentication.

## Features
- Register and Login with JWT authentication
- Token stored in HTTP-only cookie
- Protected routes (only logged-in users can access)
- Add, view, and delete own tasks
- Logout (clears cookie)
- Admin role with extra access

## Tech Used
Node.js, Express, JWT, bcryptjs, cookie-parser, dotenv

## Setup Instructions
1. Install dependencies:
   ```bash
   npm install
2. .env
3. node server.js

### production deployment URL :
https://tokencookie.onrender.com