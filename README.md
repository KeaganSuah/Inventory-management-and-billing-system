# Inventory Management System 🛒

## Introduction
This Python-based inventory management system reads a CSV file containing shoe inventory data and allows users to view and filter products by various attributes such as model number, model name, color, size, and quantity. Additionally, the system includes a billing feature that processes customer purchases and updates the inventory in real-time.

## Features & Functions
### Inventory Display
- **CSV File Handling:** The system reads inventory data from `inventories.csv` using Python's `csv` module.
- **Attribute Filtering:**
  - **Model Number:** Users can view products by entering the model number.
  - **Model Name:** Allows navigation of the inventory by model name.
  - **Size:** Displays all products matching a specific size.
  - **Color:** Filters products by color, useful for customers with color preferences.
- **Detailed Information:** Displays relevant details for each item, including model name, color, size, and available quantity.
- **Full Inventory View:** Users can choose to display all items at once.

### Billing System
- **Product Selection:** Users can choose products by model name and color.
- **Size-Specific Display:** The system presents size details after initial selection to improve user experience.
- **Transaction Processing:**
  - **Quantity Validation:** Ensures sufficient stock is available before completing a transaction.
  - **Real-Time Inventory Update:** Automatically updates the quantity in the inventory after a purchase.
- **Total Calculation:** The system keeps track of total purchase amounts and displays the final bill to the user.

## How It Works
1. **CSV Loading and Parsing:** The CSV file is loaded and parsed into a dictionary, where:
   - The **key** is the model number.
   - The **values** include model name, price, quantity, color, size, and location.
2. **Inventory Display Options:** Users can choose to filter by model number, name, size, or color.
3. **Billing Functionality:** Users can select items for purchase, input the quantity, and view the total bill. The system deducts purchased quantities from the inventory.

### Main Program Loop:
The program prompts users to choose between viewing the inventory or processing a bill. Users can exit the program by typing `end`.

## Technologies Used
- Python
- GitHub
- Pycharm

## Skills Demonstrated
- Algorithm Design
- Inventory Management
- Console-based interaction
- Data Validation

## Contact
For inquiries or feedback, please contact me at suahkeagan@gmail.com
