# E-Commerce Full-Stack Application

## Project Overview

This is a comprehensive e-commerce web application with full functionality for product management, user authentication, and shopping cart operations.

## Technology Stack

### Frontend
- React
- State Management: Custom stores
- Routing: React Router
- Key Features:
  - Authentication pages
  - Product listing and details
  - Shopping cart
  - User registration and login

### Backend
- Node.js
- Express.js
- Authentication: JWT
- Database: (Please specify your database)
- Key Features:
  - User management
  - Product CRUD operations
  - Cart management
  - Protected routes

## Project Structure

```
project-root/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   └── routes/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── config/
│
└── docs/
```

## Installation

### Prerequisites
- Node.js
- npm

### Setup Steps
1. Clone the repository
```bash
git clone [https://github.com/Dunnaya/product-store]
cd [product-store]
```

2. Install dependencies
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Configure Environment
- Create `.env` file
- Add necessary configuration (DB connections, API keys)

## Running the Application

### Development Mode
```bash
# Start backend (from backend directory)
npm run dev

# Start frontend (from frontend directory)
npm start
```

### Production Build
```bash
npm run build

## Documentation

Generate API documentation:
```bash
npm run docs
```

## Testing

### Backend Tests
```bash
cd backend
npm test
```

## Key Features

- User Registration and Authentication
- Product Management
- Shopping Cart Functionality
- Responsive Design
- Protected Routes
- State Management