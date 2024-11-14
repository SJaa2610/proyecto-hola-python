# Hello World Python Application with Flask

A basic application developed with Flask that displays the message "Hi, I'm Sarahi. This is my Python project" on the web page.

## Description

This project is a simple web application built with Flask, a lightweight web framework for Python. The application displays a message on a webpage instead of in the console. It runs inside a Docker container to make deployment and execution easier in any environment.

## Prerequisites

- **Python 3.10** or higher
- **Docker** (if you want to run the application inside a container)
- **Pip** (to install dependencies if running locally)
- **Text editor or IDE of your choice** (Visual Studio Code, PyCharm, etc.)

## Technologies Used

- **Flask** - Python web framework
- **Python 3.10**
- **Docker** (for containerized application)

## Installation and Running

### 1. Clone the repository:
```bash
git clone  https://github.com/your_username/your_repository.git
```

2. Navigate to the project directory:
```bash
cd your_repository
```

3. Install dependencies:
If you're running the application locally, you'll need to install the dependencies using pip. Make sure you have a virtual environment active or install the dependencies globally:

```bash
pip install -r requirements.txt
```

4. Run the application locally:
To run the application locally, simply run the following command:

```bash
python project.py
```
The app will run on http://0.0.0.0:8080, and you can access the message in your browser.

5. Run the application using Docker:
If you prefer to run the app in a Docker container, make sure you have Docker installed and follow these steps:

1. Build the Docker image:
```bash
docker build -t hello-python-app .
```
2. Run the container:
```bash
docker run -p 8080:8080 hello-python-app
```
The application will be available at http://localhost:8080.

Project Structure
bash
Copiar código
├── Dockerfile                 # Docker configuration to build the image
├── project.py                 # Source code of the Flask application
├── requirements.txt           # File containing the necessary dependencies for the project
└── README.md                  # This file
Configuration
No additional configuration is required to run this basic application.

Contributing
If you'd like to contribute to this project, please:

Fork the repository.
Create a new branch for your changes.
Make your changes and ensure everything works correctly.
Commit and push your changes.
Submit a pull request so we can review and merge your changes.
Author
Sarahi

Contact
GitHub: @sjaa2610
