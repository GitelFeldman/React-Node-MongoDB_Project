# Create the content as a markdown file

content = """
# 🌟 **Product Store - Final Project in React**

## **Project Description**

This is a final project developed as part of the React course. It is an online store for purchasing products that offers a user-friendly interface and a variety of features for product management, shopping cart functionality, and user management based on roles and permissions.

## **Key Features of the Project**

- **Product Listing Page**: Displays a list of products with the option for infinite scrolling (infinite scroll) or pagination.
- **Single Product Page**: Displays detailed product information including 📸, 🖊️, and 💵. Users can ➕ add products to the shopping cart 🛒.
- **Product Details Page**: Displays full product details with the option to ➕ add to cart 🛒 and shows a minimized shopping cart component.
- **Shopping Cart**: Displays all selected products with options to:
  - Update quantities
  - Remove items from the cart
  - Calculate the total price
  - Complete the order
- **User Management**: Includes login, registration, and logout screens, with handling of user roles and permissions (guest, registered user, admin).
- **Product Management**: Admins can:
  - Delete or edit products
  - Add new products

## **Technologies and Tools Used**

- **React.js**: For building the user interface and components.
- **Redux**: For managing global state, including user management, products, and the shopping cart.
- **React Router**: For navigation between pages and handling dynamic routes.
- **Axios**: For communication with the API to load and save data.
- **React Hook Form**: For handling forms in login, registration, and product addition.
- **Design Library (Bootstrap/Material-UI)**: For responsive design and modern user interface.
- **LocalStorage**: For storing user details after login.

## **Project Structure**

- **Component Slice for Each Topic**: Clear separation between user management, products, and the shopping cart.
- **API Layer**: All API calls are managed in dedicated files.
- **Secure Routing**: Protection of sensitive routes based on user roles and permissions.
- **Responsive Design**: The system is optimized for display on different devices.

## **How to Run the Project**

1. Clone the project:  
   ```bash
   git clone https://github.com/GitelFeldman/React-Node-MongoDB_Project.git
