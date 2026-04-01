# Recipe Share - MERN Stack Application

A full-stack Recipe Sharing Platform built with MongoDB, Express, React, and Node.js.

## Features
- User authentication (JWT) with role-based access (admin / user)
- Browse, search, and filter approved recipes
- Full recipe detail view with ingredients and step-by-step instructions
- User profile management (edit name, email, change password)
- Submit, edit, and delete your own recipes
- Admin dashboard with stats, category distribution, top contributors
- Admin recipe management: approve, reject, delete any recipe

## Demo Accounts (after seeding)
| Role  | Email               | Password  |
|-------|---------------------|-----------|
| Admin | admin@recipe.com    | admin123  |
| User  | sarah@recipe.com    | user123   |
| User  | mike@recipe.com     | user123   |

## Project Structure
```
recipe-share/
├── backend/          # Node.js + Express + MongoDB API
└── frontend/         # React 18 + Tailwind CSS
```

## Quick Start

### 1. Install dependencies
```bash
npm run install-all
```

### 2. Configure environment
```bash
cp backend/.env.example backend/.env
# Edit backend/.env and set MONGO_URI and JWT_SECRET
```

### 3. Seed the database
```bash
npm run seed
```

### 4. Run the app
```bash
npm start
```

- Frontend: http://localhost:3000
- Backend API: http://localhost:5001

## Tech Stack
- **Frontend**: React 18, React Router v6, Tailwind CSS, Lucide React, Axios
- **Backend**: Node.js, Express, Mongoose, JWT, bcrypt
- **Database**: MongoDB
