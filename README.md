
# Task Manager

Flask Task Manager is a simple web application built with Flask, a lightweight Python web framework, that allows users to manage their tasks efficiently.


## Features

- User Authentication: Users can register for an account and log in to access the task management features.
- Task Management: Users can add, view, update, and delete tasks. Each task includes details such as title, description, due date, and priority.
- User-Friendly Interface: The application provides an intuitive user interface for easy navigation and task management.
- Responsive Design: The application is designed to be responsive, ensuring optimal viewing and interaction across a wide range of devices and screen sizes.

## Installation

1. Clone the Repository:

```bash
  git clone https://github.com/MrKaplanP/TaskManager
```
2. Navigate to the Project Directory:
```bash
    cd TaskManager
```
3. Install Dependencies:
```bash
    pip install -r requirements.txt
```
4. Set up the Database:
```bash
    flask db init
    flask db migrate -m "Initial migration"
    flask db upgrade
```
5. Run the Application:
```bash
    python app.py
```

The application will be accessible at http://127.0.0.1:5000/ by default.
## Usage/Examples

- Register for a new account or log in with existing credentials.
- Once logged in, you can add tasks from the dashboard.


## TODOs

- [ ]  Make it more secure
- ✔Add edit, delete tasks

## Tech Stack

**Flask**: Python web framework for building the application backend.\
**SQLAlchemy**: Object-relational mapping (ORM) library for database interactions.\
**Flask-Migrate**: Extension for handling database migrations.\
**Flask-Login**: Extension for user authentication and session management.\
**Bootstrap**: Frontend framework for responsive design and styling.


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

