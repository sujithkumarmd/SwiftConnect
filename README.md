# RealTime Talker

## Overview

**RealTime Talker** is a web application that enables users to engage in real-time conversations. Built using Python Flask and Socket.IO, the platform ensures an average message delivery time of under 100 milliseconds. Users can easily create and join chat rooms, making communication seamless and instant.

## Features

- **Real-Time Communication:** Instant messaging with negligible latency.
- **Chat Rooms:** Users can create and join multiple chat rooms.
- **Efficient Performance:** Average message delivery time of under 100 milliseconds.

## Technologies Used

- **Backend:** Python, Flask, Flask-SocketIO
- **Frontend:** HTML, CSS, JavaScript
- **WebSockets:** Socket.IO

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/realtime-talker.git
   cd realtime-talker
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python main.py
   ```

5. **Open your browser and navigate to:**
   ```
   http://127.0.0.1:5000
   ```

## Usage

1. Open the application in your web browser.
2. Enter a username to join.
3. Create a new chat room or join an existing one.
4. Start chatting in real-time with other users.

## Project Structure

```
realtime-talker/
│
├── templates/
│   ├── index.html
│   └── chat.html
│
├── static/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── main.js
│
├── main.py
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.
