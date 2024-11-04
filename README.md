# Inventory-Management-Project

# Description:
Developed a comprehensive inventory management application using the MVC (Model-View-Controller) architecture. This application enables users to manage and view products with features to add new products and display them in a user-friendly manner. The design follows a clear separation of concerns, ensuring maintainability and scalability.

# Technologies Used:
  * Express.js: For creating a robust backend server to handle routes and manage application logic.
  * EJS (Embedded JavaScript Templates): For rendering dynamic HTML views and managing the layout with reusable templates.
  * Bootstrap: A powerful front-end framework for faster and easier web development, providing responsive design capabilities.
  * JavaScript (ES6+): For both client-side and server-side scripting, ensuring dynamic and interactive user experiences.

# Architecture:
Model-View-Controller (MVC) Architecture: Implemented to structure the application into three distinct layers:
 * Model: Represents the data and business logic. Defined in product.model.js, it handles data retrieval, manipulation, and storage.
 * View: Represents the presentation layer. Managed through EJS templates in the views folder, it renders the HTML content dynamically based on the data provided by the controller.
 * Controller: Manages the application's logic and user input. Defined in product.controller.js, it processes requests, interacts with the model, and updates the view accordingly.

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
  * Controller Layer (product.controller.js): Developed methods to handle product retrieval and addition. Includes validation for user inputs and error handling to manage incorrect data.
  * Model Layer (product.model.js): Implemented the ProductModel class for managing product data. Includes methods for retrieving all products and adding new ones, maintaining a static list for demonstration purposes.
  * View Layer (views/):
    * layout.ejs: Base layout for consistent header and footer across pages.
    * index.ejs: Template for displaying the product list.
    * new-product.ejs: Template for the product addition form, including error messages.
  * Error Handling:
    * Validated form inputs to ensure that all required fields are filled and that the price is positive.
    * Checked the validity of the image URL and displayed error messages for any issues.
    * Handled invalid data submissions by providing user feedback and re-rendering the form with error details.

    
# Demonstrated Skills:

  * Full-Stack Web Development
  * Implementation of MVC Architecture
  * Backend Development with Express.js
  * Frontend Development with EJS and Bootstrap
  * Error Handling and Input Validation
  * Responsive Design and User Experience
![Uploading image.png…]()
