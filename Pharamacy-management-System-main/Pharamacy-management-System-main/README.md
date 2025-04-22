# Pharmacy-management-System
# Introduction
This is a pharmacy management system built using Django. It helps pharmacy owners manage their inventory, sales, and customer information efficiently.

# Features
Inventory Management: Keep track of available medicines, their quantity, and expiry dates.
Sales Management: Record sales transactions and generate invoices.
Customer Management: Store customer information and purchase history.
User Authentication: Secure login and registration system for admin and staff members.
## Installation Instructions

Follow these steps to set up and run the Pharmacy Management System on your local machine.

### 1. Clone the Repository

Open your terminal and run the following command to clone the repository:

```bash
git clone https://github.com/DarpanYB38/pharmacy-management-system.git
```

### 2. Install Dependencies

Ensure Python is installed on your machine. Then, navigate to the project directory and install the required dependencies:

```bash
pip install django
```

### 3. Apply Database Migrations

Run the following command to apply database migrations:

```bash
python manage.py migrate
```

### 4. Create a Superuser (Admin)

Create a superuser to access the admin panel by running:

```bash
python manage.py createsuperuser
```

Follow the prompts to set up your superuser credentials.

### 5. Run the Development Server

Start the development server with the following command:

```bash
python manage.py runserver
```

### 6. Access the Application

Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access the application.

# Usage
Log in as admin using the credentials created in step 4.
Add medicines to the inventory.
Record sales transactions and generate invoices.
Manage customers and view purchase history.
Contributing
Contributions are welcome! Please follow the Contributing Guidelines.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgements
Django - The web framework used<br>
Bootstrap - Frontend framework<br>
Font Awesome - Icons<br>
