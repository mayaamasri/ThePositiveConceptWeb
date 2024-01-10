# The Positive Concept - eCommerce Website
## Table of Contents

- [Overview](#overview)
- [Technologies](#technologies)
- [Why The Positive Concept Needs a Website](#why-the-positive-concept-needs-a-website)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
- [Running Tests](#running-tests)
- [Acknowledgments](#acknowledgments)

## Overview

Welcome to The Positive Concept, an eCommerce website designed to elevate your lifestyle with motivational frames, customized cups, daily to-do lists, and yearly planners. This comprehensive proposal outlines our plan to establish a dynamic and engaging online presence for your small business.
  
## Technologies

- *Backend:* Node.js, Express
- *Database:* MySQL
- *Server Monitoring:* nodemon
- *Testing:* Postman

## Dependencies

- [body-parser](https://www.npmjs.com/package/body-parser) - Middleware to parse incoming request bodies.
- [cors](https://www.npmjs.com/package/cors) - Express middleware for enabling CORS (Cross-Origin Resource Sharing).
- [dotenv](https://www.npmjs.com/package/dotenv) - Module to load environment variables from a .env file.
- [express](https://www.npmjs.com/package/express) - Web application framework for Node.js.
- [express-validator](https://www.npmjs.com/package/express-validator) - Middleware for request validation in Express.
- [moment](https://www.npmjs.com/package/moment) - Library for handling dates and times in JavaScript.
- [mysql2](https://www.npmjs.com/package/mysql2) - MySQL library for Node.js.
- [nodemon](https://www.npmjs.com/package/nodemon) - Utility to monitor changes in your Node.js application and automatically restart the server.

## Why The Positive Concept Needs a Website

While The Positive Concept has a thriving presence on Instagram, relying solely on a social media platform poses risks. A dedicated website provides control, ensuring your business remains easily discoverable despite platform algorithm changes. This proposal details how WebWorks will create a custom website, enhancing brand recognition, and driving growth.

## Key Features

### Product Display and Customization

- *Organized Display:* Products categorized, sortable by price and categories
- *Detailed Information:* Each product includes descriptions, sizes, materials, and customizable options.

### User Interaction

- *User-Friendly:* Easy browsing without the need for login, except for placing orders or reviews.
- *Search Functionality:* Direct product search via the Search Bar for user convenience.

### User Accounts and Engagement

- *Newsletter Subscription:* Users can subscribe for updates, sales, and freebies (wallpapers, templates).
- *User Section:* Consists of Customer and Address tables for organized user management.

### Ordering and Payment

- *Shopping Cart* Temporary data stored for user convenience during product browsing.
- *Customization Table:* Stores customer preferences for personalized products.
- *Reviews and Ratings:* Build trust with a review section for each product.

### Order Management

- *Order Table:* Central table linked to users, recording all placed orders.
- *Shipment Table:* Records and verifies deliveries.

### Administration Functions

- *User:* Add, edit, or delete users with secure password hashing.

- *Address:* Add, edit, delete, and retrieve addresses.

- *Product:* Add, edit, delete, and retrieve products from a specific category or sorted by price.

- *Category:* Add, edit and delete product categories.

- *Cart* Add, delete, and edit Cart and WishList data.

- *Review:* Add and delete product reviews.



## Getting Started

To set up the project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/mayaamasri/ThePositiveConceptWeb
cd positive-concept-ecommerce

# Install dependencies
npm install
