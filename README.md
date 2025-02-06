Real-time Chat App with Flask and Socket.IO



A real-time chat application built with Flask and Socket.IO, allowing users to create or join chat rooms, send messages instantly, and see typing indicators.

Features
🔹 Real-time messaging using WebSockets
🔹 Create or join chat rooms with unique codes
🔹 Typing indicators to see when someone is typing
🔹 Persistent messages within rooms (session-based)
🔹 Dark-themed responsive UI

Installation

Prerequisites
Make sure you have Python installed (preferably 3.7 or higher).

Setup
# Clone the repository
git clone https://github.com/yourusername/your-repository.git
cd your-repository

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt


Running the Application

flask run  # OR
python app.py

The application will be accessible at http://127.0.0.1:5000/.

Usage

Open the app in a browser.
Enter a name and either create a new chat room or join an existing one using a room code.
Start chatting in real-time!

Screenshots

![image](https://github.com/user-attachments/assets/62b30cc7-898a-4780-aab3-9715fd1b5b13)
![image](https://github.com/user-attachments/assets/ec30bca7-05f0-40bb-a4ba-668ac4abaa68)

Technologies Used

Flask (Backend framework)
Socket.IO (Real-time communication)
HTML, CSS, JavaScript (Frontend UI)

License

This project is licensed under the MIT License.
