# 🎉 E-commerce Product Store - React & Node.js

Welcome to the E-commerce Product Store project! This is a full-stack application built with **React** for the front end and **Node.js** for the back end. Below you'll find a description of the project structure, features, technologies used, and how to run the app locally. 🚀

---

## 🌟 Features

### Backend (Node.js) 💻

- **Product Management**: Add, update, delete, and fetch products. Supports filtering by text search.
- **User Management**: Users can register, login, and access specific routes based on their role (USER/ADMIN).
- **Order Management**: Users can place orders, update them, and view order history. Admin can delete and manage orders.
  
### Frontend (React) 🎨

- **Product Listing**: Displays a list of all products with pagination. Each product can be viewed in more detail.
- **Shopping Cart**: Users can add products to the shopping cart and proceed to checkout.
- **User Authentication**: Users can sign up and log in to the site. The current user's name and role are shown in the navigation bar.
- **Admin Panel**: Admin users can add, edit, and delete products directly from the UI.

---

## 🛠️ Technologies Used

### Backend:
- **Node.js**: The server-side runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: Database to store user, product, and order data.
- **JWT (JSON Web Token)**: For user authentication and authorization.
- **bcryptjs**: For password hashing.
- **Joi**: For data validation.

### Frontend:
- **React**: JavaScript library for building user interfaces.
- **Redux**: For state management.
- **React Router**: For routing and navigation.
- **Axios**: For API calls to the backend.
- **CSS/HTML**: For basic styling (responsive design included).

## 🔒 Authentication & Authorization

- Users are authenticated using JWT tokens.
- Admin users have access to all product and order management routes.
- Regular users can only manage their own orders.

---

## 🎨 UI Features

- **Product List Page**: Displays all products, with pagination or infinite scrolling.
- **Product Details Page**: Shows detailed information about a product, including image, description, and price.
- **Shopping Cart**: Users can add/remove items from the cart, adjust quantities, and proceed to checkout.
- **Login/Signup Forms**: Authentication is handled with email/username and password.
- **Admin Panel**: Allows admins to manage products directly from the UI.

---

## 🔧 Troubleshooting

- **CORS Issues**: Make sure CORS is enabled on the backend by installing the `cors` package and configuring it in the server.
- **JWT Token Expiry**: Tokens expire after a set period. Make sure you handle token refresh or re-login properly.

---

## 📅 Project Milestones

- **Backend Setup**: Implemented RESTful API for product, user, and order management.
- **Frontend UI**: Developed interactive components for product listing, shopping cart, and order management.
- **Authentication**: Added JWT-based authentication with encrypted password storage.
- **Admin Features**: Added admin functionality to manage products and orders.

---

## 🎯 Future Improvements

- **Payment Integration**: Add payment gateway for real transactions.
- **Admin Dashboard**: Improve the admin panel for better management of users and orders.
- **Product Reviews**: Allow users to review products.

---

## 🤝 Contributing

Feel free to fork this project, create a pull request, and contribute to its improvement. If you have suggestions or improvements, open an issue or submit a pull request!

