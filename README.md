# Volunteer_Management_System
A web-based application for managing volunteers and events, including volunteer profiles, event assignments, notifications, and reporting.

## Features
### Volunteer Profiles:
Volunteers can create and manage their profiles, including their address, skills, availability, and a short biography.

### Event Management:
Administrators can create and manage events with detailed descriptions, required skills, urgency levels, and dates.

### Volunteer Matching:
Match volunteers to events based on their skills and availability.

### Notifications:
Notify volunteers about event assignments, updates, and reminders.

### Volunteer History:
Populate the volunteer history with there status.

### Reporting Module:
Generate reports on volunteer activities and event management, exportable as PDF or CSV.

## Technology Stack
Backend: Node.js, Express.js, MongoDB (with Mongoose)

Frontend: React.js (or HTML/CSS/JavaScript, depending on your implementation)

Database: MongoDB Atlas

Testing: Jest, Supertest

Authentication: JSON Web Tokens (JWT)

Development Tools:
Postman for API testing
MongoDB Compass for database management

## Prerequisites
Node.js installed on your system.
MongoDB Atlas account (or local MongoDB setup).
Git installed.

## Installation and Setup

Clone the repository:
git clone https://github.com/yourusername/volunteer-matching.git
cd volunteer-matching

Install dependencies:
npm install

Set up environment variables:
Create a .env file in the root directory with the following keys:
MONGO_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_jwt_secret>
PORT=5000

Start the development server:
node server.js

Run tests:
npm test

## Future Enhancements
Real-time notifications using WebSocket.
Integration with calendar APIs for event scheduling.
Enhanced analytics in the reporting module.

