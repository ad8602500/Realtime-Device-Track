Real-Time Tracker System
Overview
The Real-Time Tracker System is a web-based application that allows users to share and track their geographical locations in real-time. Built using Node.js, Express, Socket.io, and Leaflet.js, this project demonstrates real-time data transmission and updates through WebSocket technology, making it ideal for applications such as logistics, event coordination, or social meet-ups.

Features
Real-Time Location Sharing: Users' locations are tracked and shared in real-time.
Live Map Display: Users' locations are displayed on an interactive map using Leaflet.js.
Multiple Users Support: Handles multiple users, updating their locations and removing them from the map when they disconnect.
Cross-Browser Compatibility: Works across different browsers that support the Geolocation API.
Technologies Used
Backend:

Node.js
Express.js
Socket.io
Frontend:

Leaflet.js for the interactive map
EJS for rendering HTML templates
Geolocation API for fetching users' locations
Installation
Follow these steps to set up and run the project locally:

Clone the Repository

bash
Copy code
git clone https://github.com/your-username/real-time-tracker-system.git
cd real-time-tracker-system
Install Dependencies

bash
Copy code
npm install
Run the Server

bash
Copy code
npm start
Access the Application

Open your web browser and go to http://localhost:3000 to view the application.
Usage
Once the server is running, users can visit the application URL in their browser.
The application will request access to the user's location through the Geolocation API.
Users' locations will be updated in real-time on the map, which can be viewed by all connected clients.

Acknowledgments
Socket.io for real-time communication.
Leaflet.js for the interactive map.
Express.js for the web framework.
