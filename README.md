# User Management API

A TypeScript-based REST API for user management.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The server will start on port 3000 by default.

## API Endpoints

### Delete User
- **DELETE** `/api/users/:id`
  - Deletes a user by their ID
  - Returns 200 on success with message
  - Returns 404 if user not found

### List Users (for testing)
- **GET** `/api/users`
  - Returns list of all users

## Health Check
- **GET** `/health`
  - Returns API status