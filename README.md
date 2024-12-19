# SciPy Bills & Inventory Management

## Project Overview
The SciPy Billing and Inventory Management system is a desktop application developed using Python's Tkinter library. It utilizes SQLite for efficient database management. The application is structured into two main sections: Product Management (Admin) and Dashboard.

## Features
- **Login Panel**: Secure access to the product management panel via username(admin) and password (12345).
  
![image](https://github.com/user-attachments/assets/0705c610-f749-4c59-8f82-91b1c4c7eb7c)
  
- **Product Management**:
  - Add new products with fields for name, ID, price, and quantity.
  - Update existing product details.
  - Delete products from the database.
  - Display a list of all products.
    
  ![image](https://github.com/user-attachments/assets/70c2568b-04fb-44e2-b52d-7aabc0de2b93)</br>
    
- **Dashboard**:
  - Enter customer details (name, phone number, and address).
  - View product list to select items and add them to the bill area.
  - Add products to the billing area using the option panel.
  - The Database is updated after addition of every product into the cart from dashboard.
  - Calculate the total cost.
  - Calculator to calculate change.
  - Display the bill with details including product name, quantity, price, and total amount.
  - Print button to save the bill on the PC.
  - Reset the bill area using the reset button.
    
  ![image](https://github.com/user-attachments/assets/8c243ccb-e68e-41a9-9c78-4fec52a4c2ef)

## Technologies Used
- **Python**: Primary programming language.
- **Tkinter**: GUI package for Python.
- **SQLite**: Lightweight database management system.
- **Pillow**: Python Imaging Library for image processing.

## Requirements
- **Python 3.x**
- **Tkinter** (included with Python)
- **SQLite** (included with Python)
- **Pillow**: Install using `pip install pillow`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/atharvadate04/SciPy-Bills-Inventory-Management.git
2. Navigate to the project directory:
   ```bash
   cd SciPy-Bills-Inventory-Management
   
## Usage
1. Run the main application
   ```bash
   python main.py
2. Use the login panel to access the admin panel.
3. Manage products by adding, updating, or deleting them in the product management panel.
4. Use the dashboard to enter customer details, add products to the bill, calculate totals, and print receipts.

## File Structure
  ```bash
  SciPy-Bills-Inventory-Management/
│
├── main.py                # Main application code
├── ProductList.db         # SQLite database file
├── README.md              # Project documentation
└── requirements.txt       # List of dependencies
```

## Database Structure
-Database Name: ProductList.db
-Table: productlist
  - pro_name (TEXT): Name of the product.
  - pro_id (TEXT): Unique product identifier.
  - price (REAL): Price of the product.
  - quantity (INTEGER): Available quantity of the product.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository**: Click on the 'Fork' button at the top right corner of this repository.

2. **Clone your fork**: 
   ```bash
   git clone https://github.com/atharvadate04/SciPy-Bills-Inventory-Management.git
3. Create a branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
4. Make Your Changes
5. Commit Your changes:
   ```bash
   git commit -am 'Add some feature or fix some bug'
6. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
7. Create a Pull Request: Go to the original repository on GitHub and create a pull request to merge your changes into the main branch.

Please ensure your code follows the project's coding guidelines and includes any necessary tests or documentation.
Thank you for your contributions!

## Contact
- Chitraksh
  [Email](chitrakshchavan4@gmail.com)
  [Linkedin](https://www.linkedin.com/in/chitraksh-chavan-937771254/)
  [GitHub](https://github.com/Chitraksh09error)
- Atharva
  [Email](atharva40date@gmail.com)
  [Linkedin](https://www.linkedin.com/in/atharva-date-44278328a/)
  [GitHub](https://github.com/atharvadate04/)
- Jagdish
  [Email](jagdishkachhawahjk@gmail.com)
  [Linkedin](linkedin.com/in/jagdish-kachhawah-21jk)
  [GitHub](https://github.com/jagdish-kachhawah)
