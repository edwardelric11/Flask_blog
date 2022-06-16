# Flask Blog
Flask blog is a Python Flask learning project which follows the tutorial of Corey Schafer on Youtube.

## Features

- Blogspot website with multiple users
- Create, update and delete posts
- Unique id for each post and user
- Users can change their profile picture
- Gmail connection for password reset
- Structred with flask blueprint
- Custom error messages

### Flask
Flask is a micro web framework written in Python. 
It is classified as a microframework because it does not require particular tools or libraries. 

### Tech
Flask depends on the Jinja template engine and the Werkzeug WSGI toolkit. 

- Jinja - Jinja is a modern and designer-friendly templating language for Python, modelled after Django’s templates.

- Werkzeug WSGI - Werkzeug is a comprehensive WSGI(Web Server Gateway Interface) web application library. 

### Setup
1. Install Python (3.6 or later).
2. Install required packages
  - `pip install flask flask_sqlalchemy flask_wtf flask_bcrypt flask_login flask_mail Pillow`

### Running
1. To start the server: `python3 run.py`
2. Then navigate to `localhost:5000` on your browser
