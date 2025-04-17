# Library Management System

A modern and efficient Library Management System built with Flask and MySQL. This system provides a complete solution for managing library operations including book management, user management, and book issuing.

## Features

- **User Management**
  - User registration and authentication
  - Role-based access control (Admin/User)
  - Password management
  - User profile management

- **Book Management**
  - Add, edit, and delete books
  - Book categorization
  - Author and publisher management
  - Rack management for physical book organization

- **Book Issuing System**
  - Issue books to users
  - Track issued books
  - Manage return dates
  - View issue history

- **Dashboard**
  - Overview of library statistics
  - Quick access to important functions
  - User-friendly interface

## Technology Stack

- **Backend**: Python Flask
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Authentication**: Session-based

## Prerequisites

- Python 3.x
- MySQL Server
- Flask
- Flask-MySQLdb

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure MySQL:
   - Create a database named 'library-system'
   - Update the database credentials in `app.py`

5. Run the application:
```bash
python app.py
```

## Database Setup

1. Import the database dump from the `database dump` directory
2. Configure the database connection in `app.py`:
```python
app.config['MYSQL_HOST'] = 'localhost'
app.config['MYSQL_USER'] = 'your_username'
app.config['MYSQL_PASSWORD'] = 'your_password'
app.config['MYSQL_DB'] = 'library-system'
```

## Usage

1. Access the application at `http://localhost:5000`
2. Login with admin credentials:
   - Email: admin@admin.com
   - Password: admin123
3. Start managing your library!

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Screenshots

[Add screenshots of your application here]

## Contact

For any queries or support, please contact [your-email@example.com] 