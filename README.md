# Django Chat Application

[![Django](https://img.shields.io/badge/Django-4.2.4-brightgreen.svg)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.11.5-blue.svg)](https://www.python.org/)

The Django Chat Application is a simple chat platform built with Django and WebSocket technology.

## Features

- **Create Chat Rooms**: Set up your own chat rooms and moderate discussions.
- **User-Friendly Interface**: A clean and intuitive design for an enhanced user experience.

## Prerequisites

Before you get started, ensure you have the following prerequisites in place:

- **Python**: Version 3.11.5 installed on your local machine. [Download Python](https://www.python.org/downloads/)
- **Django**: Version 4.2.4 installed. [Install Django](https://www.djangoproject.com/download/)
- **Git**: Installed on your system for cloning the repository. [Install Git](https://git-scm.com/downloads)

## Installation and Setup

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/trial-start/django-chat.git
    cd django-chat
    ```

2. **Create and Activate a Virtual Environment** (Optional but Recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. **Apply Migrations to Set Up the Database**:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

4. **Create a Superuser (Admin) Account** (Optional):

    ```bash
    python manage.py createsuperuser
    ```

5. **Start the Development Server**:

    ```bash
    python manage.py runserver
    ```

6. **Access the Chat Application**:

    Open your web browser and navigate to [http://127.0.0.1:8000](http://127.0.0.1:8000) to start using the chat application.

## Usage

1. **Open the Chat Application**: Open your web browser and navigate to the chat application's URL.

2. **Enter a Chat Room**:
   - **Create a New Chat Room**:
     - Enter a room name in the "Room Name" input field.
     - Enter your username in the "Username" input field.
     - Click the "Enter Room" button.
     - You'll become the moderator of the new chat room.

   - **Join an Existing Chat Room**:
     - Navigate to same chat application's URL in a new tab
     - Enter the name of the chat room you want to join in the "Room Name" input field.
     - Enter your username in the "Username" input field.
     - Click the "Enter Room" button.
     - You'll join the existing chat room as a participant.




