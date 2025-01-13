# iyrtW

**if you're reading this... WAIT**

## Overview

iyrtW is a web application built with the Django framework. It features functionalities such as user account management, content management, and media handling.

## Features

- **User Accounts**: Manage user registrations, logins, and profiles.
- **Content Management**: Create, edit, and delete articles or blog posts.
- **Media Handling**: Upload and manage media files associated with content.

## Project Structure

- **accounts/**: Contains modules related to user authentication and profile management.
- **articles/**: Manages the creation and display of articles or blog posts.
- **assets/**: Houses static files like images, CSS, and JavaScript.
- **blog/**: Oversees the blogging functionalities of the application.
- **media/**: Stores uploaded media files.
- **templates/**: Includes HTML templates for rendering views.
- **db.sqlite3**: SQLite database file for development and testing.
- **manage.py**: Command-line utility for administrative tasks.

## Technologies Used

- **Django**: High-level Python web framework.
- **SQLite**: Lightweight database for development purposes.
- **HTML/CSS/JavaScript**: Frontend technologies for the user interface.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/xmadoyx/iyrtW.git

2. **Navigate to the project directory**:
   ```bash
   cd iyrtW

3. **Create and activate a virtual environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate

4. **Install dependencies**:
   ```bash
   pip install -r requirements.txt

5. **Apply migrations**:
   ```bash
   python manage.py migrate

6. **Run the development server**:
   ```bash
   python manage.py runserver

7. **Access the application**: Open a web browser and navigate to <http://127.0.0.1:8000/>.

## Contribution Guidelines

Contributions are welcome! Please fork the repository and create a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
