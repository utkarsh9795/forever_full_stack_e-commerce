# FOREVER : E-Commerce Project

## Overview
FOREVER is a full-stack e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js) and integrated with Stripe and Razorpay for secure and flexible payment options. The platform offers a seamless user experience, with features that allow users to browse, search, and filter products, add items to the cart, and manage their orders. For site administrators, a custom admin panel enables easy management of products and order statuses.

## Features

### 1. Home Page
- **Latest Collection**: Displays recently added products with transition effects, showcasing product titles and prices.
- **Best Sellers**: Highlights the best-selling products to capture user interest.
- **Policy Section**: Informative section outlining user-friendly policies such as:
  - Easy Exchange Policy
  - 7-Day Return Policy
  - Dedicated Customer Support
- **Subscription Section**: Allows users to sign up for updates and promotions.
- **Footer**: Contains essential links, social media handles, and contact information.

### 2. Collection Page
- **Product Display**: Shows all products available on the website.
- **Filter Options**:
  - **Categories**: Filter by Men, Women, Kids.
  - **Product Types**: Filter by Topwear, Bottomwear, Winterwear.
  - **Sort Order**: Sort products by price (Low to High, High to Low).
- **Search Bar**: Search products by keywords for quick access to desired items.

### 3. About Page
- **Product Showcase**: Highlights a specific product with its detailed description to give users insight into product quality and brand vision.

### 4. Contact Page
- **Store Locations**: Provides information on store locations.
- **Job Exploration**: Lists open job positions for potential applicants.

### 5. User Authentication
- **Sign-In and Sign-Up Pages**: Secure and easy-to-use authentication system for users to create accounts and manage orders.

### 6. Product Page
- **Product Gallery**: Located on the left side, displaying high-quality images of the product.
- **Product Details**: Right side details including:
  - Product Title
  - User Reviews
  - Price
  - Product Description
  - Available Sizes
  - Add-to-Cart Option
- **Related Products**: Displays similar products to enhance the shopping experience.

### 7. Cart Page
- **Cart Management**:
  - Increase/Decrease Quantity
  - Remove Products
  - View Cart Totals
- **Checkout Process**: On proceeding, the user is taken to a checkout page where:
  - Delivery details can be added.
  - Payment method selection (Stripe, Razorpay, Cash on Delivery) is available.
- **Order Placement**: After placing an order, users can view their order summary.

### 8. My Orders Page
- **Order Tracking**: Users can view their orders, with details such as:
  - Product Title
  - Price
  - Quantity
  - Size
  - Order Date
  - Payment Status
- **Order Status**: Track the status of each order as it progresses from order placed to delivery.

### 9. Admin Panel
- **Admin Login**: Secured login page with email and password authentication.
- **Dashboard Features**:
  - **Add Items**: Allows admin to upload new products, with fields for title, description, price, category, and image upload.
  - **List Items**: Displays all products currently available on the platform, with editing options.
  - **Orders Management**: Track and update the order status through stages:
    - Order Placed
    - Packing
    - Shipped
    - Out for Delivery
    - Delivered

## Technology Stack
- **Front-end**: React
- **Back-end**: Express.js, Node.js
- **Database**: MongoDB
- **Payment Gateways**: Stripe, Razorpay

This robust e-commerce solution caters to both users and administrators, providing a complete shopping experience and backend management system. The project demonstrates the power of the MERN stack in building a full-featured online store.
