# Event Management System
## Overview
This project is an Event Management System (Attendee module) that allows users to view, create, and manage events, tickets, profile and notifications. It includes features such as user authentication, event listing, event details, and notifications for various actions like event insertion, updation, and cancellation.

## Table of Contents
- Features
- Technology Stack
- Project Structure
- Installation
- Usage
- API Endpoints
- License

## Features
- User Authentication (Login, Logout)
- User Profile Management
- Event Listing and Details
- Ticket Management
- Notifications for Insertion, Updation, and Cancellation of Events

## Technology Stack
### Frontend
- React
- React Router
- Axios (for API requests)
- CSS (for styling)
### Backend
- Node.js
- Express.js
- MongoDB (or any preferred database)
- JWT (for authentication)
- Mongoose (for MongoDB object modeling)

## Project Structure
## Frontend

src/

├── components/

│     ├── Notification.js

│     ├── InsertionNotification.js

│     ├── UpdationNotification.js

│     └── CancellationNotification.js

│     ├── EventDetail.js

│     ├── EventTile.js

│     ├── Login.js

│     ├── Logout.js

│     ├── Profile.js

│     ├── Home.js

│     ├── Navbar.js

│     ├── TicketDetails.js

│     ├── Tickets.js

├── App.js

└── index.js

## Backend

src/

├── controllers/

│   ├── authController.js

│   ├── eventController.js

│   ├── ticketController.js

│   └── notificationController.js

├── models/

│   ├── User.js

│   ├── Event.js

│   ├── Ticket.js

│   └── Notification.js

├── routes/

│   ├── authRoutes.js

│   ├── eventRoutes.js

│   ├── ticketRoutes.js

│   └── notificationRoutes.js

├── middleware/

│   └── authMiddleware.js

├── config/

│   └── db.js

├── server.js

└── app.js

## Installation

### Prerequisites
- Node.js and npm
- MongoDB

## Backend Setup

### Clone the repository:

- git clone https://github.com/yourusername/event-management-system.git
- cd event-management-system/backend

### Install backend dependencies:

- npm install

### Run the backend server:

- npm start

## Frontend Setup
### Navigate to the frontend directory:

- cd frontend

### Install frontend dependencies:

- npm install

### Start the frontend development server:

- npm start

## Usage
- Open your browser and navigate to http://localhost:3000 for the frontend.
- The backend server runs on http://localhost:5000.

## API Endpoints
### Authentication
- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login a user
- POST /api/auth/logout - Logout a user
### Events
- GET /api/events - Get all events
- GET /api/events/:id - Get event by ID
- POST /api/events - Create a new event
- PUT /api/events/:id - Update an event
- DELETE /api/events/:id - Delete an event
### Tickets
- GET /api/tickets - Get all tickets
- GET /api/tickets/:id - Get ticket by ID
- POST /api/tickets - Create a new ticket
- PUT /api/tickets/:id - Update a ticket
- DELETE /api/tickets/:id - Delete a ticket
### Notifications
- GET /api/notifications - Get all notifications
- POST /api/notifications - Create a new notification

## License
This project is licensed under the MIT License. 
