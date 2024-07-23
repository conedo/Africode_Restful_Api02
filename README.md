# Flask-RESTful and API Application

This is a simple Flask web application that allows users to create and manage a blog. The application uses Flask-SQLAlchemy for database operations and Flask-RESTful for API endpoints.

## Features

- Users can create, read, update, and delete (CRUD) their own posts.
- Users can view all posts created by other users.
- Each post has a title, content, and creation timestamp.
- Users can view the username of the author of each post.

## Getting Started

To clone and use this application, follow these steps:

1. Install Python 3.x and pip.
2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate (Linux/macOS)
   venv\Scripts\activate (Windows)
   ```
3. Clone the repository:
   ```
   git clone https://github.com/your-username/flask-blog-app.git
   cd flask-blog-app
   ```
4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Create the SQLite database:
   ```
   python
   from app import db
   db.create_all()
   exit()
   ```
6. Run the application:
   ```
   python run.py
   ```
7. Access the application in your browser at http://localhost:5000.

## Contributing

To contribute to this project, follow these steps:

1. Fork the repository on GitHub.
2. Clone your fork:
   ```
   git clone https://github.com/your-username/flask-blog-app.git
   cd flask-blog-app
   ```
3. Create a new branch for your changes:
   ```
   git checkout -b your-feature-branch
   ```
4. Make your changes and commit them:
   ```
   git add .
   git commit -m "Add your commit message"
   ```
5. Push your changes to your fork:
   ```
   git push origin your-feature-branch
   ```
6. Create a pull request on GitHub to merge your changes into the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.