# E-Shop - Modern E-Commerce Platform

A full-stack e-commerce platform built with React, Node.js, and MongoDB. This project provides a modern shopping experience with features like user authentication, product browsing, cart management, and secure checkout.

## Features

### User Features
- User authentication (Login/Register)
- Product browsing with categories and subcategories
- Product search and filtering
- Shopping cart management
- Secure checkout process
- Order history
- User profile management

### Admin Features
- Product management (CRUD operations)
- Order management
- User management
- Category management
- Sales analytics

## Tech Stack

### Frontend
- React.js
- React Router for navigation
- Context API for state management
- Axios for API requests
- Material Icons for UI elements
- CSS3 with modern features

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt for password hashing

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/e-shop.git
cd e-shop
```

2. Install dependencies for both frontend and backend:
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Create a `.env` file in the server directory:
```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the development servers:
```bash
# Start backend server
cd server
npm run dev

# Start frontend server
cd ../client
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

## Project Structure

```
e-shop/
├── client/                 # Frontend React application
│   ├── public/            # Static files
│   └── src/
│       ├── components/    # React components
│       ├── context/       # Context providers
│       ├── pages/         # Page components
│       └── App.js         # Main application component
│
├── server/                # Backend Node.js application
│   ├── config/           # Configuration files
│   ├── controllers/      # Route controllers
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   └── server.js         # Server entry point
│
└── README.md             # Project documentation
```

## API Endpoints

### Authentication
- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login user
- GET /api/auth/profile - Get user profile

### Products
- GET /api/products - Get all products
- GET /api/products/:id - Get product by ID
- POST /api/products - Create new product (admin)
- PUT /api/products/:id - Update product (admin)
- DELETE /api/products/:id - Delete product (admin)

### Categories
- GET /api/categories - Get all categories
- POST /api/categories - Create new category (admin)
- PUT /api/categories/:id - Update category (admin)
- DELETE /api/categories/:id - Delete category (admin)

### Orders
- GET /api/orders - Get user orders
- POST /api/orders - Create new order
- GET /api/orders/:id - Get order by ID

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/)
- [Material Icons](https://material.io/resources/icons/)

## Contact

Your Name - your.email@example.com
Project Link: [https://github.com/yourusername/e-shop](https://github.com/yourusername/e-shop) 