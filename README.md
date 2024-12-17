Final Project - React E-Commerce Store (2024)
Project Requirements
A React-based e-commerce store where users can browse, add products to the cart, and manage orders. Below are the implemented features:

1. Products Page 🛍️
Display products fetched from the server.
Support pagination or infinite scroll.
2. Single Product Page 📦
Show product image, description, price, and "Add to Cart" button.
Clicking a product navigates to the product's detail page.
3. Product Detail Page 📝
Full product details with a unique URL.
Allow users to add products to the cart, with a temporary cart notification.
4. Mini Cart 🛒
Show products added to the cart (no edit option).
5. Shopping Cart Page 💳
Display products in the cart with price, quantity, and total cost.
Allow updating quantities or removing items.
"Continue Shopping" and "Complete Order" buttons.
Order confirmation sends cart data to the server.
6. Login Page 🔑
User login form (email/username & password).
Successful login stores user data in redux and redirects to the Products page.
7. Registration Page ✍️
User registration form (email/username, password, etc.).
On success, save user details in redux and localStorage.
Option to log out, which clears localStorage.
8. Admin Features 👨‍💻
Admins see "Delete" and "Edit" buttons for products.
Deleting a product shows a confirmation prompt.
Editing products opens a form pre-filled with product data.
9. Add Product Page ➕
Form for adding new products (name, price, image URL, etc.).
10. NavBar 🌐
Displays the logged-in user's name or "Guest."
Conditional navigation based on user role (Guest, Registered User, Admin).
Additional Features:
Product Search/Sorting 🔍: Search by name or filter by categories/price range.
Update Product Page ✏️: Edit existing products with pre-filled data using react-hook-form.
Notes:
Responsiveness: Styled using a UI library (e.g., Material-UI).
Server Interaction: Handled through API calls for products, authentication, and cart data.
Deployment: The project is deployed on Netlify.
