# Webstore App

This is a full-stack web application built with React, Bootstrap, MERN (MongoDB, Express, React, Node), PayPal API, JWT (JSON Web Tokens), and QR code.

Features
Browse and search products
Add products to cart
Checkout using PayPal API
User authentication and authorization using JWT
QR code generation and scanning
Getting Started
Prerequisites
Before running this app, you need to have the following software installed on your machine:

Node.js
MongoDB
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/mimickStern/Mickey-Slug.git
Install dependencies for the front-end:

bash
Copy code
cd frontend
npm install
Install dependencies for the back-end:

bash
Copy code
cd ../backend
npm install
Configure environment variables:

Create a .env file in the backend directory with the following variables:

makefile
Copy code
PORT=5000
MONGO_URI=<your MongoDB connection string>
JWT_SECRET=<your JWT secret>
PAYPAL_CLIENT_ID=<your PayPal client ID>
Seed the database:

arduino
Copy code
npm run data:import
This will seed the database with sample products and users.

Start the development server:

arduino
Copy code
npm run dev
This will start both the front-end and back-end servers.

Open your browser and go to http://localhost:3000 to see the app.

Usage
Browse products: On the home page, you can see a list of all the products available in the store. You can search for products by name or category using the search bar.

Add products to cart: Click the "Add to Cart" button to add a product to your cart. You can view your cart by clicking the cart icon in the top right corner of the page.

Checkout using PayPal: When you're ready to checkout, click the "Checkout" button in your cart. You'll be redirected to PayPal to complete the payment process. After completing the payment, you'll be redirected back to the app.

User authentication: To create an account or log in, click the "Sign In" button in the top right corner of the page. Once you're logged in, you'll be able to view your order history and manage your account.

QR code generation and scanning: When you place an order, a QR code will be generated that contains your order information. You can scan this QR code using a QR code scanner app to view your order details.

Contributing
If you'd like to contribute to this project, please follow these steps:

Fork this repository.

Create a new branch for your changes.

Make your changes and commit them.

Push your changes to your fork.

Submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
