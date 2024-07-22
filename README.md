# Inventory-Management-Project

# Description:
Developed a comprehensive inventory management application using the MVC (Model-View-Controller) architecture. This application enables users to manage and view products with features to add new products and display them in a user-friendly manner. The design follows a clear separation of concerns, ensuring maintainability and scalability.

# Technologies Used:
  * Express.js: For creating a robust backend server to handle routes and manage application logic.
  * EJS (Embedded JavaScript Templates): For rendering dynamic HTML views and managing the layout with reusable templates.
  * Bootstrap: A powerful front-end framework for faster and easier web development, providing responsive design capabilities.
  * JavaScript (ES6+): For both client-side and server-side scripting, ensuring dynamic and interactive user experiences.

# Project Structure:
  * index.js: The entry point of the application.
  * controllers/product.controller.js: Contains the logic for handling product-related routes.
  * models/product.model.js: Defines the product model and handles data storage and retrieval.
  * views/: Contains EJS templates for rendering the UI.
  * public/: Contains static assets like CSS and client-side JavaScript.

# Key Features:

  * Product Listing: Displays a comprehensive table of products with details such as ID, name, description, price, and image.
  * Add New Product: Provides a form to add new products to the inventory, with input validation to ensure data integrity.
  * Responsive Design: Utilizes Bootstrap to ensure a responsive and user-friendly interface across different devices.
  * Error Handling: Implements robust error handling to manage invalid inputs and provide user feedback.
  
# Technical Details:

  * Server Setup (index.js):  Configured an Express.js server with middleware for JSON and URL-encoded data. Set up EJS as the view engine and defined routes for displaying products and handling product submissions.
  * Product Controller (product.controller.js): Developed controller methods for retrieving and adding products, including input validation and error handling.
  * Product Model (product.model.js): Created a product model class to manage product data, including static methods for retrieving and adding products.
  * Views: Designed EJS templates for rendering the product list and product addition form, integrated with Bootstrap for styling.
  * Error Handling:
    * Validated user inputs for product name, price, and image URL to ensure correct data entry.
    * Provided user feedback on form submission errors, such as missing required fields or invalid URL formats.

    
# Demonstrated Skills:

  * Full-Stack Web Development
  * Backend Development with Express.js
  * Frontend Development with EJS and Bootstrap
  * Error Handling and Input Validation
  * Responsive Design and User Experience
