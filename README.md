# Django Chat Application

[![Django](https://img.shields.io/badge/Django-3.2.4-brightgreen.svg)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.9.5-blue.svg)](https://www.python.org/)

The Django Chat Application is a real-time chat platform built with Django and WebSocket technology. It empowers users to create chat rooms, join existing ones, and engage in real-time conversations. With its user-friendly interface, connecting with friends, colleagues, or online communities has never been easier.

## Features

- **Create Chat Rooms**: Set up your own chat rooms and moderate discussions.
- **Real-Time Messaging**: Enjoy seamless real-time communication within chat rooms.
- **User-Friendly Interface**: A clean and intuitive design for an enhanced user experience.

## Prerequisites

Before you get started, ensure you have the following prerequisites in place:

- **Python**: Version 3.9.5 installed on your local machine. [Download Python](https://www.python.org/downloads/)
- **Django**: Version 3.2.4 installed. [Install Django](https://www.djangoproject.com/download/)
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

    Open your web browser and navigate to [http://localhost:8000](http://localhost:8000) to start using the chat application.

## Usage

1. **Open the Chat Application**:

   Open your web browser and navigate to the URL where you've hosted the chat application.

2. **Create or Join a Chat Room**:

   - **Create a New Chat Room**: Click on the "Create New Room" button or a similar option (if available). Enter a room name or choose one, and you'll become the moderator.
   - **Join an Existing Room**: To join an existing chat room, click on the "Join Room" button or a similar option. Enter the room's name or select from the available rooms. You'll join the chat as a participant.

3. **Start Sending Real-Time Messages**:

   Once you're inside a chat room, start sending real-time messages to other participants. Simply type your message in the text input field and press Enter or click the "Send" button.

Enjoy seamless real-time communication with the Django Chat Application!

