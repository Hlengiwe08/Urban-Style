# UrbanStyle E-Commerce Website

## Project Overview
UrbanStyle is a responsive e-commerce website for a fashion brand specializing in trendy clothing and accessories.  
The site allows customers to browse products, add them to a cart, and proceed to checkout.  

This project was developed as an **individual assignment** and deployed using GitHub Pages.  

---

## Features Implemented
- **Home Page**
  - Welcome text
  - Promotional banner
  - Featured products section

- **Products Page**
  - Displays all available products in a grid layout
  - Each product includes an image, price, and "Add to Cart" button
  - **Search bar** to filter products by name

- **Product Details Page** 
  - Each product card links to more details (image, description, price, Add to Cart)

- **Cart Page**
  - Displays all items added to cart
  - Allows quantity updates
  - Remove items from cart
  - Calculates total cost

- **Checkout Page**
  - Simple form for customer details (name, email, address, payment method)
  - **Form validation** using JavaScript
  - Confirmation alert on successful order

- **Contact Us Page**
  - Contact form with name, email, message
  - Store details: email, phone number

- **Responsive Design**
  - Works on mobile, tablet, and desktop devices

---

## How It Works
- Products are stored in a **JavaScript array** inside `script.js`.
- When a user clicks "Add to Cart", the item is saved in **localStorage** so it persists across pages.
- The **Cart Page** dynamically loads cart items, allowing updates and deletions.
- The **Search bar** filters products in real time.
- The **Checkout form** validates input fields before confirming an order.

---

##  Challenges Faced
- Implementing **cart persistence** across multiple pages without a backend → solved using `localStorage`.
- Designing a **responsive grid layout** for products → solved using CSS Grid and media queries.
- Ensuring smooth **form validation** on the checkout page → solved with JavaScript event listeners.
- Simulating a payment process without a backend → limited to form validation and confirmation message.

---

## Completed Features
- Core pages (Home, Products, Cart, Checkout, Contact)
- Add to Cart / Remove / Update quantity
- Cart total calculation
- Responsive design
- Search functionality
- Form validation

---

## Bonus Features
- Product categories (e.g., Men, Women, Accessories)
- Sorting by price or name
- Customer reviews
- Dark mode toggle

---

## 📂 Project Structure
