# django-chat
The Django Chat Application is a real-time chat platform built with Django and WebSocket technology. It allows users to create chat rooms, join existing ones, and engage in real-time conversations. The user-friendly interface makes it easy to connect with friends, colleagues, or online communities instantly.

![Django](https://img.shields.io/badge/Django-4.2.4-brightgreen.svg)
![Python](https://img.shields.io/badge/Python-3.11.5-blue.svg)

This is a real-time chat application built using Django and WebSocket technology.

## Features

- Create chat rooms.
- Real-time messaging within rooms.
- User-friendly interface.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.9.5 installed on your local machine.
- Django 3.2.4 installed.
- Git installed (for cloning the repository).

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/django-chat.git
   cd django-chat

2. Create and activate a virtual environment (optional but recommended):
  python -m venv venv
  source venv/bin/activate  # On Windows, use: venv\Scripts\activate

3. Install the project dependencies:
   pip install -r requirements.txt

4.Apply migrations to set up the database:
  python manage.py makemigrations
  python manage.py migrate

5.Create a superuser (admin) account(optional:
  python manage.py createsuperuser

6.Start the development server:
  python manage.py runserver

7.Open your web browser and navigate to http://localhost:8000 to access the chat application.

## Usage

1. **Open the Chat Application**: Open your web browser and navigate to the URL where you've hosted the chat application.

2. **Create or Join a Chat Room**:
   - **Create a New Chat Room**: If you want to create a new chat room, click on the "Create New Room" button or a similar option, if available. Enter a room name or choose one, and you'll be the moderator.
   - **Join an Existing Room**: To join an existing chat room, click on the "Join Room" button or a similar option. Enter the room's name or select from the available rooms. You'll join the chat as a participant.

3. **Start Sending Real-Time Messages**: Once you're inside a chat room, you can start sending real-time messages to other participants. Simply type your message in the text input field and press Enter or click the "Send" button.
  

 



   
