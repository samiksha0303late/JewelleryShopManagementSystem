# Jewellery Shop Management System

## Project Overview
The Jewellery Shop Management System is a web-based e-commerce application developed to make online jewellery shopping easier and more convenient. Users can explore jewellery products, create accounts, add products to their cart, place orders and track their purchases.

The system also provides an admin dashboard to manage products, categories, users and orders.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Development Environment:** XAMPP
- **Code Editor:** Visual Studio Code

## Features

### User Features
- User registration and login
- Browse jewellery collections
- View product details
- Search and explore products
- Shopping cart management
- Checkout and order placement
- Order tracking
- User profile management
- Offers and new arrivals

### Admin Features
- Admin dashboard
- Manage products
- Manage product categories
- Manage customer information
- Manage customer orders

## Project Folder Structure

```text
jewellery-shop/
│
├── admin/
├── auth/
├── images/
├── includes/
├── legacy/
├── uploads/
├── user/
│
├── index.php
├── offers.php
├── style.css
├── database.sql
└── README.md
```

## Installation and Setup

Follow these steps to run the project locally.

1. Install XAMPP on your computer.
2. Start Apache and MySQL from the XAMPP Control Panel.
3. Download or clone this repository.
4. Extract the project folder into:

   `F:\xampp\htdocs\`

5. Open phpMyAdmin in your browser:

   `http://localhost/phpmyadmin`

6. Create a database named `jewellery`.
7. Import the `database.sql` file into the database.
8. Check the database configuration in `includes/Config.php`.
9. Open the project in your browser:

   `http://localhost/jewellery-shop/`

## Database

The project uses MySQL to store application data.

Main database tables include:
- users
- categories
- products
- cart
- orders
- order_items

## Testing

The following areas can be tested locally:

- User registration and login
- Product browsing
- Shopping cart operations
- Checkout and order placement
- Order tracking
- Admin product and category management
- Admin order and user management

## Project Objective

The main objective of this project is to develop an easy-to-use online jewellery shopping platform that provides product browsing, shopping cart functionality, order management and administrative control.

## Future Enhancements
- Improved responsive design
- Enhanced form validation
- Image optimization
- Improved accessibility
- Online deployment
- Enhanced security and performance

## Author
**Renuka Gajbhar**

GitHub: https://github.com/Renuka-Gajbhar

Repository: https://github.com/Renuka-Gajbhar/JewelleryShopManagementSystem