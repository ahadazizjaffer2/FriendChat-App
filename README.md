# FriendChat App

# Real-Time Chat Application

## Overview

This Real-Time Chat Application is a web-based platform that facilitates real-time communication between users in designated chat rooms. It includes features such as user authentication, room creation and management, and real-time messaging using Socket-IO Library.

## Features

- **User Authentication**: Sign up and log in functionalities.
- **Chat Room Management**: Create, edit, and view chat rooms.
- **Real-Time Messaging**: Send and receive messages in real-time.
- **Join/Leave Notifications**: Notifications for users joining or leaving chat rooms.
- **Responsive Design**: Optimized for various devices and screen sizes.

## Technology Stack

- **Backend**: Flask, Flask-SocketIO, Flask-Login
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MongoDB
- **WebSocket**: Flask-SocketIO
- **HTTP Protocol**: Flask for HTTP requests
- **Network Security**: HTTPS, CORS

## Installation

### Prerequisites

- Python 3.8 or higher
- MongoDB

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/real-time-chat-application.git
    cd real-time-chat-application
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the environment variables:
    ```bash
    export FLASK_APP=app.py
    export FLASK_ENV=development
    export SECRET_KEY='your_secret_key'
    export MONGO_URI='your_mongodb_connection_string'
    ```

5. Run the application:
    ```bash
    flask run
    ```

6. Run the SocketIO server:
    ```bash
    python app.py
    ```

7. Access the application at `http://127.0.0.1:5000`

## Network Architecture

The Real-Time Chat Application employs a client-server architecture, using Flask for handling HTTP requests and WebSocket for real-time communication. The network stack includes:

- **TCP**: Reliable, connection-oriented transport protocol used by WebSocket for real-time messaging.
- **WebSocket**: Facilitates instant message delivery between clients and the server.
- **HTTP**: Used for standard client-server communication, including authentication and page requests.
- **CORS**: Ensures secure cross-origin requests.

## Security Measures

- **HTTPS**: Encrypts data transmitted between the client and server.
- **CORS**: Restricts resources to be accessed from trusted origins only.
- **Session Management**: Protects against unauthorized access by securely managing user sessions.

## Usage

1. **Sign Up**: Create a new account on the signup page.
2. **Log In**: Log in using your credentials on the login page.
3. **Dashboard**: View all available chat rooms.
4. **Create Room**: Create a new chat room and add members.
5. **Edit Room**: Edit room details and manage members if you are an admin.
6. **Join Room**: Join a chat room to send and receive messages in real-time.
7. **Logout**: Log out from your account.

## Contact

For any inquiries or feedback, please contact ahadaziz4@gmail.com

---

Thank you for using the FriendChat Application!
