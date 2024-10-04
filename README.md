# Online-Inventory-Management-System-using-Python

Overview

The "Inventory Management System" is a GUI-based application developed using Python and Tkinter that allows users to manage product inventories easily. Users can add products, specify quantities and prices, and store this information in a MySQL database. The application provides a simple and intuitive interface for inventory management, making it suitable for small businesses or personal use.

Features

- User-friendly GUI built with Tkinter.
- Ability to add products with their details (name, stock, price).
- Data is stored in a MySQL database.
- Provides feedback messages for actions (success/error).
- Reset functionality to clear input fields.

Requirements

- Python 3.x
- Tkinter (usually included with Python installations)
- MySQL Connector for Python
- MySQL Server

Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rawat28/Online-Inventory-Management-System-using-Python.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Online-Inventory-Management-System-using-Python
   ```

3. Install the required packages:

   You can install the necessary packages using pip:

   ```bash
   pip install mysql-connector-python
   ```

4. Set up MySQL Database:

   - Create a MySQL database named `inventory_system`.
   - Create a table named `inventory` with the following schema:

     ```sql
     CREATE TABLE inventory (
         id INT AUTO_INCREMENT PRIMARY KEY,
         name VARCHAR(255) NOT NULL,
         stock INT NOT NULL,
         price DECIMAL(10, 2) NOT NULL
     );
     ```

## Usage

1. Run the application:

   ```bash
   python main.py
   ```

2. The application window will open. You can:

   - Enter the product details (name, stock, price).
   - Click the "Update the database" button to add the product to the database.
   - Use the "Reset the fields" button to clear the input fields.

3. Any inserted product details will be displayed in the log area.

Contributing

Contributions are welcome! If you have suggestions for improvements or want to report issues, please feel free to create an issue or submit a pull request.


## Acknowledgments

- [Tkinter](https://docs.python.org/3/library/tkinter.html) for GUI development.
- [MySQL](https://www.mysql.com/) for database management.

```

