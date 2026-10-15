ShopKart - Full-Stack E-Commerce Application
A complete full-stack MERN e-commerce web application featuring user authentication, product catalog browsing, cart management, wishlist functionality, and order processing.

Features
User Authentication: Secure JWT-based login, registration, and role-based access.

Product Management: Product catalog with filtering, details view, and inventory tracking.

Shopping Cart & Wishlist: Real-time cart state management, counter badges, and wishlist toggle.

Order Handling: Order checkout flow and status tracking.

Responsive UI: Modern design built with React, Vite, and Tailwind CSS.

Tech Stack
Frontend: React, Vite, React Router, Axios, Tailwind CSS

Backend: Node.js, Express.js, JSON Web Tokens (JWT), bcrypt

Database: MongoDB & Mongoose ODM

Setup Instructions
Prerequisites
Node.js (v16+ recommended)

MongoDB connection URI (local instance or MongoDB Atlas)

Backend Setup
Open a terminal and navigate to the backend folder:
cd backend

Install dependencies:
npm install

Create a .env file in the backend/ directory with:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Start the backend development server:
npm run dev

Frontend Setup
Open a new terminal tab and navigate to the frontend folder:
cd frontend

Install dependencies:
npm install

Start the Vite development server:
npm run dev

Core API Endpoints
POST /api/auth/register : Register a new user account

POST /api/auth/login : Authenticate user and receive token

GET /api/products : Retrieve product list

GET /api/products/:id : Fetch details of a specific product

GET /api/cart : Get current user active cart

POST /api/cart : Add product to shopping cart

POST /api/orders : Place a new order
