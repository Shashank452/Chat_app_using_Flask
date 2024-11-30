# Chatter-Box

Chatter-Box is a lightweight and easy-to-use real-time chat application built using Flask and Flask-SocketIO. It allows users to create or join chat rooms and communicate seamlessly with others in real time.

## Features

- **Room Creation**: Users can generate unique room codes to start their own private chat rooms.
- **Join Rooms**: Join an existing room using its unique code.
- **Real-time Messaging**: Enjoy real-time communication with other members in the room.
- **Persistent Chat**: Messages in a room remain available for all participants until the room is empty.
- **User-friendly UI**: Simple and intuitive design for effortless interaction.

## Tech Stack

- **Backend**: Flask, Flask-SocketIO
- **Frontend**: HTML, CSS (via Flask templates)
- **Database**: In-memory storage (Python dictionaries)

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/ajaythandavamurthy/messanger-chatting.git
    cd messanger-chatting
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    python main.py
    ```

4. Open your browser and navigate to `http://127.0.0.1:5000`.

## Usage

1. **Home Page**:
   - Enter your name.
   - Choose to create a new room or join an existing one using a room code.

2. **Chat Room**:
   - Start chatting in real-time with other members in the room.
   - Messages from all participants appear instantly.

3. **Disconnect**:
   - When a user leaves the room, other members are notified.

## Folder Structure

```plaintext
Chatter-Box/
├── main.py                # Main application file
├── templates/
│   ├── base.html         
│   ├── home.html         # Home page template
│   └── room.html         # Chat room template
├── static/
│   ├── style.css         # Custom styles (optional)
├── requirements.txt      # Required Python packages
└── README.md             # Project documentation
