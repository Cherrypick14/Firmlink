# Firmlink Project

Firmlink is a Django-based platform that allows users to sign up and log in as either customers or companies. The project includes role-based authentication, custom user management, and email-based login, with a focus on flexibility and scalability.

## Features

- **Role-based User Authentication**: Users can register as either `customers` or `companies`.
- **Custom User Model**: The project uses a custom `User` model that extends Django's `AbstractUser` to handle email-based login and custom user roles.
- **User Registration**: Separate forms and views for customer and company sign-ups.
- **Email Login**: The login system authenticates users via email instead of the default username.
- **Company and Customer Profiles**: Customers have a birthdate, and companies have a field of service and rating.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Cherrypick14/firmlink.git
   ```

2. Navigate to the project directory:

   ```bash
   cd firmlink
   ```

3. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - **macOS/Linux**:

     ```bash
     source venv/bin/activate
     ```

   - **Windows**:

     ```bash
     venv\Scripts\activate
     ```
5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   pip freeze requirements.txt
   ```
6. Apply migrations:
   
     ```
   python manage.py migrate

   ```
7. Create a superuser:

   ```
   python manage.py createsuperuser

   ```
8. Run the development server:

   ```
   python manage.py runserver

   ```
9. Contribution

   Feel free to fork the repository, make improvements, or report issues. Contributions are welcome!

10. LICENSE

    This project is licensed under the MIT License 

