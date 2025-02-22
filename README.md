# Food Ordering System (Khayali Pulaw)

A web-based food ordering application built using **Streamlit** and **MySQL**. This project provides an interactive interface where users can create accounts, browse restaurants and menus, place orders, and track their order history.

## Features

- **User Account Creation:** Register new users with basic information.
- **Browse Restaurants:** View available restaurants along with details like address, cuisine, and ratings.
- **View Menus:** Explore food menus with item names, prices, categories, and associated restaurant details.
- **Order Placement:** Select a user, restaurant, and menu item to place an order with a specified quantity.
- **Order Tracking:** Display recent orders with order IDs, user names, restaurant names, total amounts, and order status.

## Technologies Used

- **Python**
- **Streamlit** – For building the interactive web interface.
- **MySQL** – For the backend database.
- **MySQL Connector/Python** – For connecting the application to MySQL.

## Setup & Installation

### Prerequisites

- Python 3.x prefered on VS code
- MySQL server (installed and running)
- A MySQL database (e.g., `KHAYALI_PULAW`) with the necessary tables (Users, Restaurants, Menu, Orders, OrderDetails)

### steps:
- 1) Install Required Python Packages:
- pip install streamlit mysql-connector-python
- 2) Configure the Database Connection:
- conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="12345",
    database="KHAYALI_PULAW"
)
- 3) Run the Application:
- streamlit run FOOD_DELIVERY.PY



