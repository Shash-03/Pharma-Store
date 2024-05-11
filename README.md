# Pharmaceutical Management System
## About 
Pharmaceutical Management System is a data management system for an online pharmaceutical store. It is a full-stack project developed as the Final Project for the course CSE202: Fundamentals of Database Management System.

## Instructions to Run

1. Open the folder in your terminal.
2. Navigate to the backend folder:
    ```
    cd Backend
    ```
3. Start the backend server:
    ```
    flask run
    ```
4. Navigate back to the main folder:
    ```
    cd ..
    ```
5. Navigate to the frontend folder:
    ```
    cd frontend
    ```
6. Install the node dependencies:
    ```
    npm install
    ```
7. Open up the webpage:
    ```
    npm start
    ```
8. The initial page is for user login/signup. To login as a manager or admin, append "/login_emp" to the home page address.

## Features

### User Side

1. **Sign Up/Login**: Users can sign up or login.
2. **Add to Cart**: Users can add products to their cart.
3. **Checkout**: Users can proceed to checkout from the cart.
4. **Discount Coupons**: Users can apply discount coupons during checkout.
5. **Purchase**: Users can confirm their purchases.

### Admin Side

1. **Admin Login**: Admin can log in from the employee login portal.
2. **User Data Analysis**: Admin can analyze user attributes like membership type and total expenditure.
3. **Warehouse Performance Analysis**: Admin can monitor warehouse attributes like orders and revenue.
4. **Restock Items**: Admin can replenish low-stock items in all warehouses.
5. **Inventory Management**: Admin can view and modify product quantities and thresholds across warehouses.
6. **Product Management**: Admin can view all products, register new ones, or delete existing ones.

### Manager Side

1. **Manager Login**: Managers can log in from the employee login portal.
2. **User Data Analysis**: Managers can analyze user attributes like membership type and total expenditure.
3. **Warehouse Performance Analysis**: Managers can monitor warehouse attributes like orders and revenue.
4. **Restock Items**: Managers can replenish low-stock items in their warehouse.
5. **Inventory Management**: Managers can view and modify product quantities and thresholds in their warehouse.
6. **Product Management**: Managers can view all products and add new ones to their warehouse.






