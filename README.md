# Note Taking Web Application

This is a full-stack note-taking web application built with React and Django. It allows users to register, log in, and create, view, and delete their notes.

## Project Overview

This project is a simple yet functional note-taking application that demonstrates the integration of a React frontend with a Django REST framework backend. It includes user authentication (login/register) and basic CRUD (Create, Read, Update, Delete) functionality for notes.

## Tech Stack

### Frontend

- **React:** A JavaScript library for building user interfaces.
- **Vite:** A fast build tool and development server for modern web projects.
- **React Router:** For client-side routing.
- **Axios:** A promise-based HTTP client for making requests to the backend.
- **JWT Decode:** For decoding JSON Web Tokens.

### Backend

- **Django:** A high-level Python web framework.
- **Django REST Framework:** A powerful and flexible toolkit for building Web APIs.
- **Simple JWT for Django:** A JSON Web Token authentication plugin for the Django REST Framework.
- **SQLite:** The default database for development.

## Functionalities

- User registration and login
- Create new notes
- View all existing notes
- Delete notes

[![Watch the video](https://user-images.githubusercontent.com/122405175/281026027-a16df538-900a-4712-a720-41712776df9f.png)](https://private-user-images.githubusercontent.com/122405175/534821239-42e366f1-b8d2-4e18-a78a-4f082c5a26d3.mp4?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjgyNTg4MjcsIm5iZiI6MTc2ODI1ODUyNywicGF0aCI6Ii8xMjI0MDUxNzUvNTM0ODIxMjM5LTRmMDgyYzVhMjZkMy5tcDQ_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMTEyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDExMlQyMjU1MjdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZGEyYTY5YjQ5NjMwM2RlM2FkOGQ4Y2QyZmM2YTI2ZTdhNGI1NTVmYzYzYWZiMmUxNDY1MjE0NDQ3ZTUxODQ3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.cfAe8PyV9UAWPTnXm859R1H0ZMRV0NzRCS3V2D9tbuI)

## Setup and Installation

To run this project locally, you will need to set up both the frontend and backend services.

### Backend Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-folder>/backend
    ```

2.  **Create a virtual environment and activate it:**
    ```bash
    python -m venv myenv
    source myenv/bin/activate
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the database migrations:**
    ```bash
    python manage.py migrate
    ```

5.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

    The backend will be running at `http://127.0.0.1:8000/`.

### Frontend Setup

1.  **Navigate to the frontend directory:**
    ```bash
    cd ../frontend
    ```

2.  **Install the dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    ```

    The frontend will be running at `http://localhost:5173/`.

## Credit

This project was created by following the tutorial by **Mishal** on YouTube. You can find the video tutorial [here](https://youtu.be/c-QsfbznSXI).