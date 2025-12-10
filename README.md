

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

## Screenshots

### Registration Page:


<img width="1911" height="908" alt="Screenshot 2025-12-10 223024" src="https://github.com/user-attachments/assets/916b089f-5207-4414-949d-bf0426eb15b2" />


### Products Page:


<img width="1890" height="907" alt="Screenshot 2025-12-10 223149" src="https://github.com/user-attachments/assets/1406cd60-5404-42b4-b8d6-36c1c4757b16" />

### Cart Page:


<img width="1897" height="906" alt="Screenshot 2025-12-10 223230" src="https://github.com/user-attachments/assets/dda9f1a4-bf41-40c9-943e-ab9498a3fd79" />

### Profile Page


<img width="1900" height="911" alt="Screenshot 2025-12-10 223257" src="https://github.com/user-attachments/assets/00e05701-2ae4-4060-b3bc-e56056ae660a" />





