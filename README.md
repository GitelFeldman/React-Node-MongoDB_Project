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

---

## ⚙️ Project Setup

### 1. Backend Setup 🖥️

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/e-commerce-project.git
