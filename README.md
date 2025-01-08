Full-Stack E-commerce Website
Overview
This project is a comprehensive full-stack e-commerce platform that allows users to browse products, add items to their cart, and proceed to checkout.
The application is built using the MERN stack, providing a robust and scalable solution for online shopping experiences.

Features
User Authentication: Secure user registration and login functionality.
Product Management: Display a list of products with details.
Shopping Cart: Add products to the cart and manage quantities.
Checkout Process: Complete orders with a seamless checkout experience.
Order History: Users can view their past orders.
Technologies Used
Frontend: React.js, HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
State Management: Redux
Authentication: JSON Web Tokens (JWT)
Installation and Setup
Clone the Repository:

Installation Setup
Prerequisites
Install Node.js (Skip if already installed):
Visit the official Node.js website: Node.js Download
Download and run the installer.
Follow the prompts to complete the installation.
MongoDB Setup:
Visit MongoDB Atlas.
Sign up and log in.
Create a new project and build a database:
Select M0 Free Tier, choose your region, and create the database.
Set up a username and password.
Add IP 0.0.0.0/0 to the access list.
Copy the connection string (select the Compass option) and replace <password> with your database password.
Backend Setup
Open the project folder in VS Code.
Open the integrated terminal:
Right-click on the sidebar and select Open in Integrated Terminal.
Run the following commands:
Install dependencies:
npm install
Start the backend server:
node .\index.js
Ensure the connection string in index.js is updated with your MongoDB credentials.
Frontend & Admin Panel Setup
Open the project folder in VS Code.
Open the integrated terminal:
Right-click on the sidebar and select Open in Integrated Terminal.
Run the following commands:
Install dependencies:
npm install
Start the frontend:
npm start
The project will open in your default web browser.



Usage
Browse Products: View the list of available products on the homepage.
User Registration/Login: Create a new account or log in with existing credentials.
Add to Cart: Select products and add them to your shopping cart.
Checkout: Proceed to checkout to place your order.
View Orders: Access your order history through the user profile.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.


Acknowledgements
React.js for the frontend framework.
Node.js and Express.js for the backend server.
MongoDB for the database solution
