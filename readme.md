# Blog Boilerplate

A simple blog boilerplate built with Python Flask, featuring user registration, login, and basic blog post management.

## Features

- User registration and authentication (login/logout)
- Create, edit, and delete blog posts
- View all posts or posts by user
- SQLite database integration
- Simple, clean UI with Bootstrap

## Requirements

- Python 3.7+
- Flask
- Flask-Login
- Flask-SQLAlchemy
- Flask-WTF

## Installation

```bash
git clone https://github.com/yourusername/blog-boilerplate.git
cd blog-boilerplate
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
flask run
```

Visit `http://127.0.0.1:5000` in your browser.

## Configuration

Edit `config.py` to set your secret key and database URI.

## Folder Structure

```
blog-boilerplate/
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
│   ├── forms.py
│   └── templates/
├── static/
├── config.py
├── requirements.txt
└── readme.md
```

## License

MIT License