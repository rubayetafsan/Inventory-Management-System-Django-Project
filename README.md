# Inventory Management System

A web-based Inventory Management System built with Django, designed to streamline inventory tracking, stock management, and reporting for businesses. This project provides a user-friendly interface for managing products, categories, suppliers, and inventory transactions.

## Features
- **Product Management**: Add, update, and delete products with details like name, category, quantity, and price.
- **Inventory Tracking**: Monitor stock levels with real-time updates on incoming and outgoing inventory.
- **Supplier Management**: Maintain supplier details and associate them with products.
- **User Authentication**: Secure login and registration system for admin and staff users.
- **Reporting**: Generate basic reports for inventory status and transaction history.
- **Responsive Design**: Accessible on both desktop and mobile devices.

## Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default, configurable for PostgreSQL or others)
- **Other Tools**: Django ORM, Django Admin

## Installation

### Prerequisites
- Python 3.8+
- pip (Python package manager)
- Virtualenv (recommended)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rubayetafsan/Inventory-Management-System-Django-Project.git
   cd Inventory-Management-System-Django-master
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Database Migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a Superuser (Admin)**:
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```
   Access the app at `http://127.0.0.1:8000/`.

## Usage
- **Admin Panel**: Log in at `/admin` using the superuser credentials to manage products, suppliers, and users.
- **Dashboard**: View inventory summaries and perform actions like adding stock or updating products.
- **Reports**: Navigate to the reports section to download or view inventory data.

## Project Structure
```
Inventory-Management-System-Django-master/
├── inventory/                # Main Django app
├── templates/                # HTML templates
├── static/                   # CSS, JS, and other static files
├── manage.py                 # Django management script
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, reach out to [rubayetafsan](https://github.com/rubayetafsan) or open an issue on GitHub.
