# Flask Server for Patient Portal

This project is a basic **Flask** server that serves as the backend for a Patient Portal. The server is deployed on **Heroku** and interacts with client-side frontends. The server is lightweight and easy to set up, making it ideal for small applications or proof-of-concepts.

## Features
- **Basic routing**: Routes for `/` and other endpoints.
- **Built-in web server**: Uses Flask's `app.run()` for local development and `gunicorn` for production.
- **Heroku deployment**: Easily deploy this server to Heroku.

## Prerequisites

Before running this application, ensure you have the following installed:
- Python 3.6 or higher
- Git (for version control and repository management)
- Heroku account (optional, for deployment)

## Project Structure
```bash
.
├── app.py                # Main Flask app
├── requirements.txt       # Python dependencies
├── Procfile               # Heroku process file for running the server
└── README.md              # Project documentation
```

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/YourUsername/flask-server.git
    cd flask-server
    ```

2. **Install dependencies**:

    Install the dependencies listed in `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the server locally**:

    Run the Flask server on your local machine:

    ```bash
    python app.py
    ```

    The server will be available at `http://127.0.0.1:5000/`.

## Deployment

To deploy this project to **Heroku**, follow these steps:

1. Create an account on [Heroku](https://www.heroku.com).
2. Install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) (if you have access to a CLI tool).
3. Create a new Heroku app:

    ```bash
    heroku create
    ```

4. Push your code to Heroku:

    ```bash
    git push heroku main
    ```

5. Open your app in the browser:

    ```bash
    heroku open
    ```

## Routes

The following are the available routes:

- **`/`**: Home route, returns a "Hello, this is your Flask server running!" message.
- You can add more routes to `app.py` as needed.

## Contributing

Feel free to fork this project, open an issue, or submit pull requests to improve the functionality. Contributions are always welcome.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions, feel free to reach out to me at `your-email@example.com`.

---

### Example Usage:
```bash
# Running the server locally
$ python app.py

# Expected output:
# * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
