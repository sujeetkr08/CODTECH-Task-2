CHAT APPLICATION

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SUJEET KUMAR

*INTERN ID* : CT04DF1733

*DOMAIN* : FULL STACK WEB DEVELOPMENT

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

*DISCRIPTION* :

This repository contains the complete source code for a fully functional real-time chat application developed using HTML, CSS, JavaScript, and Node.js with Socket.IO for real-time communication. The goal of this project is to demonstrate how client-server communication works in real time, where multiple users can join, send, and receive messages instantly across all connected clients without needing to refresh the page.

🌟 Key Features
Real-time bi-directional messaging using Socket.IO

Built with HTML, CSS, and vanilla JavaScript for the frontend

Node.js and Express.js used to build the backend server

Messages broadcast to all connected users instantly

Clean and responsive UI

Easy to run locally on any system

Simple structure for beginner-friendly understanding

🏗️ Project Structure
The project is organized into two main parts: Frontend and Backend.

Frontend:

index.html provides the chat interface with a text box and send button.

style.css styles the interface to make it user-friendly and visually appealing.

The frontend also includes client-side JavaScript to connect to the WebSocket server using Socket.IO and handle sending/receiving chat messages.

Backend:

server.js is the main server file. It sets up an Express server, serves static files, and initializes the WebSocket server using Socket.IO.

The server listens for incoming socket connections and handles broadcasting messages to all connected clients.

⚙️ Technologies Used
HTML5: Provides the basic structure of the user interface.

CSS3: Adds styling and improves the visual layout.

JavaScript (Vanilla): Adds client-side interactivity and Socket.IO integration.

Node.js: Used to build a scalable and efficient server.

Express.js: Simplifies HTTP server creation and serves static files.

Socket.IO: Powers real-time, event-based communication between clients and the server.

🚀 How It Works
A user opens the web page served by the Node.js server.

When a message is typed and submitted, JavaScript emits a chat message event using Socket.IO to the server.

The server listens for this event and broadcasts the message to all connected clients.

Each client receives the message and dynamically updates the chat interface without reloading the page.

This real-time functionality is made possible using WebSockets through the Socket.IO library, which abstracts the low-level complexity and makes real-time communication seamless and efficient.

🧪 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/chat-application.git
cd chat-application
Install dependencies:

bash
Copy
Edit
npm install
Run the server:

bash
Copy
Edit
node server.js
Open your browser and go to:

arduino
Copy
Edit
http://localhost:3000
Open multiple tabs or devices to test real-time chat.

📚 Learning Outcomes
This project is great for beginners and intermediate developers who want to:

Understand how to set up a Node.js + Express server

Learn about WebSockets and how real-time data flow works

Work with frontend-backend communication using JavaScript

Build a functional web app with live interactions.

*OUTPUT* :

![Image](https://github.com/user-attachments/assets/1dac9694-7462-4ba1-b328-7be7da8b0b5a)
