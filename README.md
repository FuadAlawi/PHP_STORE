# Fuad Store - PHP CRUD Application

A simple product management application built with PHP and SQLite.

## Features

- **View Products** - Display all products with prices
- **Add Product** - Create new products
- **Edit Product** - Update existing products
- **Delete Product** - Remove products
- **JSON API** - RESTful API endpoint

## Tech Stack

- PHP 8.x
- SQLite Database
- Bootstrap 5

## Getting Started

```bash
# Clone the repository
git clone https://github.com/FuadAlawi/PHP_STORE.git
cd PHP_STORE

# Start PHP development server
php -S localhost:8080

# Open in browser
open http://localhost:8080/index.php
```

## API Endpoint

**GET** `/api.php` - Returns all products as JSON

```json
{
  "status": "success",
  "data": [
    {"id": 1, "name": "Product Name", "price": 9.99}
  ]
}
```

## Author

Fuad Alawi
