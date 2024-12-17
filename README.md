Online Store (React Project)
🛒 Overview
This is a project developed as a final project for React, where I created an online store where users can view, purchase, and manage products. The application allows for a complete shopping experience, including product pages, shopping cart, and user registration/login features.

📝 Requirements
1. Product List Page
Displays products fetched from the server, allowing for pagination (scroll to the bottom or use buttons).
No need for product filtering.
2. Single Product Page
Displays product details: image, description, and price.
Includes an "Add to Cart" button.
Clicking on a product takes you to the product detail page.
3. Product Detail Page
Shows complete details for each product, with a unique URL.
Allows users to add the product to the shopping cart.
Displays a small cart component for a few seconds or until manually closed after adding a product.
4. Mini Cart Component
Displays products in the cart without allowing addition or deletion of items.
5. Shopping Cart Page
Displays products in the cart: image, name, unit price, quantity, and total price.
Allows users to modify quantities or remove items.
Shows total products and total amount.
Includes buttons to continue shopping or complete the order.
"Complete Order" button triggers a prompt for entering an address and confirming the order, saving the order on the server.
6. Login Page
Contains fields for email/username and password.
Displays success or error message upon login.
Upon successful login, stores user information (name, id, role, token) in Redux.
Redirects to the home page on successful login.
7. Registration Page
Similar to the login page, but for new users.
Stores user information (name, id, role, token) in Redux and localStorage.
8. Admin Features
In the "All Products" page, admins see "Delete" and "Edit" buttons instead of "Add to Cart."
Deleting a product prompts a confirmation message.
Editing a product opens a form pre-filled with current product details.
9. Add Product Page
Admins can add new products with fields for product details.
Image field accepts a URL (image uploading not implemented).
10. NavBar
Displays the current user's name or "Guest."
Navigation links are displayed based on user role (Admin, Registered User, Guest).
Admin has links for "Add Product" and "All Products."
11. Role-Based Access Control
Restrict access to certain pages based on user roles (Admin, Registered User, Guest).
If a user tries to access a restricted page directly via URL, they are redirected accordingly.
🔧 Technologies Used
React for building the user interface.
Redux for managing global state (user data, cart).
React Router for page navigation.
Axios for API calls to interact with the backend server.
React Hook Form for handling form inputs and validation.
Material UI for design components.
