# Paradise Nursery – Shopping Cart Application

Repository Name: **e-plantShopping**

This project is a React and Redux based shopping cart application developed as part of the **IBM Front-End Development course final project**.

The application simulates an online plant store called **Paradise Nursery**, where users can browse different categories of houseplants and add them to a shopping cart.

## Features

### Landing Page

* Displays the **Paradise Nursery** welcome page.
* Includes a background image and company description.
* Provides a **Get Started** button that navigates to the product listing page.

### Product Listing Page

* Displays multiple categories of houseplants.
* Each plant shows:

  * Thumbnail image
  * Plant name
  * Price
  * Description
* Includes **Add to Cart** buttons.
* The button becomes **disabled after adding a plant to the cart**.

### Navigation Header

The header appears on both the product listing page and the cart page and includes:

* Home link
* Plants link
* Shopping cart icon
* Dynamic cart counter showing the total number of items.

### Shopping Cart

The cart page allows users to:

* View all plants added to the cart
* See plant thumbnails, names, and prices
* Increase or decrease quantity
* Remove plants from the cart
* See the total cost of all items
* Continue shopping
* Checkout (Coming Soon feature)

## Technologies Used

* React
* Redux Toolkit
* React Redux
* Vite
* JavaScript
* CSS
* GitHub

## Project Structure

```
src/
  AboutUs.jsx
  App.jsx
  App.css
  CartItem.jsx
  CartSlice.jsx
  ProductList.jsx
  store.js
  main.jsx
```

## Deployment

The project can be deployed using **GitHub Pages**.

Example URL format:

```
https://username.github.io/e-plantShopping/
```

## Author

Final Project for **IBM Front-End Development Course**
