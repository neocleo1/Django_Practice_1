# Django Practice Project

A basic Django web application for learning and practicing Django fundamentals.

## Project Structure

This is a simple Django project with the following structure:
- **Main project** (`myproject/`) - Contains project configuration and core views
- **Posts app** (`posts/`) - A Django app for handling blog posts functionality
- **Templates** - HTML templates with a shared layout
- **Static files** - CSS styling and JavaScript

## Features

- **Homepage** - Welcome page with navigation
- **About page** - Simple about page
- **Posts section** - Basic posts listing (ready for expansion)
- **Responsive navigation** - Clean navigation bar with emoji icons
- **Static file handling** - CSS and JavaScript integration
- **Template inheritance** - Uses Django's template system with a base layout

## Setup Instructions

### Prerequisites
- Python 3.x
- Django 5.1.5

### Installation

1. Clone or download this project
2. Navigate to the project directory:
   ```bash
   cd myproject
   ```

3. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install Django:
   ```bash
   pip install django
   ```

5. Run migrations:
   ```bash
   python manage.py migrate
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

7. Open your browser and go to `http://127.0.0.1:8000`

## URL Routes

- `/` - Homepage
- `/about/` - About page
- `/posts/` - Posts listing page
- `/admin/` - Django admin interface

## Project Components

### Apps
- **posts** - Handles blog post functionality (currently basic, ready for models and views)

### Templates
- `layout.html` - Base template with navigation and common structure
- `home.html` - Homepage template
- `about.html` - About page template
- `posts/posts_list.html` - Posts listing template

### Static Files
- `css/style.css` - Main stylesheet with dark theme
- `js/main.js` - JavaScript file

## Development Notes

This project uses:
- SQLite database (default Django setup)
- Django's built-in development server
- Template inheritance for consistent styling
- Static files configuration for CSS/JS
