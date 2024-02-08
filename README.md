# Flask Blog
<img src="https://images.ctfassets.net/23aumh6u8s0i/4YerAVrYhtjxF95kqweaqO/fca050605d0727f9a07d8874c331405c/angular-python-flask-1">

---

flask-blog is a simple web application built using Flask, a lightweight WSGI web application framework in Python. It allows users to create, read, update, and delete blog posts.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Create, Read, Update, Delete (CRUD) Operations**: Users can create new blog posts, view existing posts, edit their own posts, and delete their posts.
- **Responsive Design**: The application is designed to be responsive, ensuring a seamless experience across various devices and screen sizes.
- **Rich Text Editor**: A user-friendly rich text editor is integrated to facilitate easy content creation.
- **Commenting System**: Users can leave comments on blog posts.
- **Tagging System**: Posts can be tagged with relevant keywords for better organization and searchability.
- **Pagination**: The list of blog posts is paginated to improve performance and user experience.

## Installation

1. Clone the repository:

```
git clone https://github.com/sinanazem/flask-blog.git
```

2. Navigate to the project directory:

```
cd flask-blog
```

3. Create a virtual environment:

```
python3 -m venv venv
```

4. Activate the virtual environment:

- On macOS and Linux:

```
source venv/bin/activate
```

- On Windows:

```
venv\Scripts\activate
```

5. Install the dependencies:

```
pip install -r requirements.txt
```

6. Set up the database:

```
flask db init
flask db migrate -m "Initial migration"
flask db upgrade
```

7. Run the application:

```
flask run
```

The application will be accessible at `http://localhost:5000` by default.

## Usage

- Visit `http://localhost:5000` in your web browser to access the application.
- Sign up for a new account or log in with an existing one.
- Create new blog posts, edit existing ones, or delete posts as needed.
- Leave comments on blog posts to engage with other users.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README file according to your project's specific requirements and features.
