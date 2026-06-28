# Furni Store (Laravel E‑Commerce)

A simple e-commerce project built with Laravel and MySQL.

## Features
- Product listing (Shop page) loaded via API (`/api/products`)
- Session-based Cart:
  - Add to cart
  - Update quantity
  - Remove item
  - View cart via API (`/api/cart`)
- Checkout (Lab 13):
  - Saves order into MySQL tables: `orders` and `order_items`
  - Clears cart after placing an order
  - Redirects to Thank You page
- Admin Product CRUD (Lab 14):
  - Manage products from `/admin/products`

## Tech Stack
- Laravel (PHP)
- MySQL
- Blade templates + Bootstrap
- JavaScript (Fetch API)

---

## Project Setup

### 1) Install dependencies
```bash
composer install
