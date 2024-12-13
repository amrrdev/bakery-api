bekrey-api/
├── config/
│ └── Database.php # Database connection logic
├── services/
│ ├── ProductService.php # Handles product-related business logic
│ ├── UserService.php # Handles user-related business logic
│ └── OrderService.php # Handles order-related business logic
├── controllers/
│ ├── ProductController.php # API logic for products
│ ├── UserController.php # API logic for users
│ └── OrderController.php # API logic for orders
├── routes/
│ ├── product.php # Product-related routes
│ ├── user.php # User-related routes
│ └── order.php # Order-related routes
├── public/
│ └── index.php # Entry point for the application
├── utils/
│ └── ResponseHelper.php # Helper functions for JSON responses
└── README.md # Project overview and setup instructions
