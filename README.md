

# SmartShop Portal

### Multi-Page Web Application

**Tech Stack:** HTML, CSS, JavaScript, REST APIs

---

## Overview

SmartShop Portal is a multi-page web application built using Vanilla JavaScript, DOM manipulation, and public APIs (Fake Store API and JSONPlaceholder).
The project demonstrates form validation, API integration, LocalStorage usage, and dynamic DOM rendering.

---

## Features

### 1. User Registration (register.html)

* Form fields: Name, Email, Password, Confirm Password
* Validations:

  * Email format
  * Password minimum 6 characters
  * Password and confirm password match
* Stores user data in LocalStorage
* Redirects to products.html
* Inline validation error handling

---

### 2. Product List (products.html)

* Fetches product data from Fake Store API

  * `https://fakestoreapi.com/products`
* Displays product cards with:

  * Image
  * Title
  * Price
  * Add to Cart button
* Adds products to LocalStorage
* Cart count displayed in the header
* Handles loading and API failure states

---

### 3. Shopping Cart (cart.html)

* Loads cart items from LocalStorage
* Displays:

  * Product title
  * Price
  * Remove button
* Shows total price dynamically
* Displays “Cart is empty” when no items exist

---

### 4. User Profile (profile.html)

* Fetches dummy user details from JSONPlaceholder

  * `https://jsonplaceholder.typicode.com/users/1`
* Displays:

  * Name
  * Email
  * Address
* Also displays registered user data saved in LocalStorage
* Includes a “Clear Data & Logout” button that:

  * Clears LocalStorage
  * Redirects to register.html

---

## Bonus Features


* Product filtering by category
* Sorting by price (ascending / descending)

---

## Project Structure

```
SmartShop-Portal/
│── register.html
│── products.html
│── cart.html
│── profile.html
│── README.md
```

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Fetch API
* LocalStorage
* Fake Store API
* JSONPlaceholder API

---

## How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Open the project (VS Code Live Server recommended).

3. Start from:

```
register.html
```

4. Register → explore products → add to cart → view cart → view profile.

---




