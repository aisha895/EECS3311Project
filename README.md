# Warehouse Management System

The system is designed to manage product orders, inventory levels, and restocking processes efficiently, incorporating features such as user authentication, order processing, and a GUI for visualization.


## About the Project
The Warehouse Management System automates order processing and inventory management for a warehouse. Key functionalities include:

1. Placing and processing orders.
2. Real-time inventory updates.
3. Restocking products when inventory falls below minimum levels.
4. User authentication via a login system.
5. Visualization of inventory levels using both text and bar charts.

## Features

### Order Processing:
1. Place orders for products.
2. Calculate the total price for orders.
3. Handle cases where orders exceed available stock or maximum allowed quantity.

### Inventory Management:
1. Automatic restocking when inventory falls below the minimum threshold.
2. Integration with a database to fetch and update product details.

### User Authentication:
1. Login system with username and password validation.
2. Implements a proxy pattern for secure authentication.

### GUI for Visualization:
1. Interactive interfaces for login and placing orders.

## Technologies Used

1. Java: Core programming language.
2. SQLite: Database for product and login information.
3. JFreeChart: For graphical visualization of inventory data.
4. Swing: For creating graphical user interfaces.
5. HTTPServer: For server-client communication.
6. JDBC: For database connectivity.
