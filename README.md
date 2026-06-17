# Online Complaint Management System

## Overview

The Online Complaint Management System is a full-stack web application that allows users to register, log in, submit complaints, and track their complaint status. The system helps organizations manage and resolve complaints efficiently through a centralized platform.

## Features

* User Registration and Login
* Submit New Complaints
* View Complaint History
* Track Complaint Status
* Secure Authentication
* MongoDB Database Integration
* Responsive User Interface

## Tech Stack

### Frontend

* React.js
* React Context API
* Axios
* CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

## Project Structure

backend/

* API Routes
* Controllers
* Models
* Middleware
* MongoDB Configuration

frontend/

* React Components
* Context API
* Pages
* Services

## Installation

### Clone Repository

git clone https://github.com/AsmithaReddy741/Online_complaint_system.git

### Backend Setup

cd backend
npm install
npm start

### Frontend Setup

cd frontend
npm install
npm start

## Environment Variables

Create a .env file in the backend directory and configure:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

## Usage

1. Register a new account.
2. Login with your credentials.
3. Submit complaints.
4. Track complaint status.
5. Manage complaints through the dashboard.

## Future Enhancements

* Email Notifications
* Complaint Categorization
* Admin Analytics Dashboard
* File Attachments
* Real-Time Status Updates

## Author

Asmitha Reddy
