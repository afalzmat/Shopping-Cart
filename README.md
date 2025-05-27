# Shopping Cart

A responsive e-commerce interface with product search and display capabilities. This project is designed to streamline product catalog management while providing a solid foundation for future expansions.

## Technologies Used

Frontend: HTML, CSS, JavaScript.

Backend: PHP with centralized routing.

Database: MariaDB.

## Project Structure
```
Shopping-Cart/
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── php/
│   ├── get_products.php
│   ├── search_products.php
│   └── connection.php
├── data/
│   └── schema.sql
└── index.html
```
## Current Features

Search for products using keywords.

Filter products by categories.

Display products in responsive design cards.

## In Progress

Shopping Cart: Add functionality to select products, manage them in a cart, and confirm purchases.

Purchase Summary: Design a section to display the history of completed purchases.

## Installation

1. Clone this repository:

git clone <repository URL>

2. Import the schema.sql file located in the data/ folder to your MariaDB server.

3. Configure the database credentials in php/connection.php.

4. Open index.html in your browser.

## Next Steps

Implement an authentication system for registered users.

Add support for multiple payment methods.

---

Developed by AFAlzMat.

