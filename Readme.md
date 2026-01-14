# Academia-Synapse [Student Management System (SMS)]

A full-stack application for managing student records, built with Node.js/Express/MongoDB for the backend and React for the frontend.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Running Tests](#running-tests)
- [API Endpoints](#api-endpoints)

## Features

- **CRUD Operations**: Complete functionality to Create, Read, Update, and Delete student records.
- **Frontend/Backend Separation**: Clear separation between the React UI and the REST API.
- **Unit Tested**: Both the API (Jest/Supertest) and the UI components (Jest/RTL) are covered with unit tests.
- **Persistent Data**: Uses MongoDB to store student data permanently.

## Technologies Used

### Backend (Node.js/Express)
- **Node.js**: Runtime environment.
- **Express.js**: Web application framework for REST API.
- **MongoDB**: NoSQL database.
- **Mongoose**: ODM for MongoDB.
- **Jest & Supertest**: For API unit and integration testing.

### Frontend (React)
- **React**: JavaScript library for building the UI.
- **Axios**: HTTP client for API communication.
- **Jest & React Testing Library (RTL)**: For component unit testing.

## Project Structure

The project is divided into two main folders: `backend` for the API and `frontend` for the UI.

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

-   **Node.js** (v18 or higher)
-   **npm** (Node Package Manager)
-   **MongoDB** (A running instance of MongoDB, either local or cloud-based)

### Backend Setup

1.  **Navigate to the backend directory:**
    ```bash
    cd student-management-system/backend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Configure environment variables:**
    Create a file named `.env` in the `backend` directory and paste the content provided in the code section, updating `MONGODB_URI` if necessary.
4.  **Start the backend server:**
    ```bash
    npm run dev
    # Server runs on http://localhost:5000
    ```

### Frontend Setup

1.  **Open a new terminal and navigate to the frontend directory:**
    ```bash
    cd student-management-system/frontend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the frontend development server:**
    ```bash
    npm start
    # Application opens at http://localhost:3000
    ```

## Running Tests

npm install concurrently --save-dev

### Backend Tests

Run unit tests for the API (requires MongoDB instance to be running):

```bash
cd student-management-system/backend
npm test

Frontend TestsRun unit tests for the React components:Bashcd student-management-system/frontend
npm test
API EndpointsAll backend API endpoints are prefixed with /api.
----------------------------------------------------------------------
Method    |    Endpoint             |    Description
----------------------------------------------------------------------
GET       |    /api/students        |    Get all students
GET       |    /api/students/:id    |    Get a single student by ID
POST      |    /api/students        |    Create a new student
PUT       |    /api/students/:id    |    Update a student by ID
DELETE    |    /api/students/:id    |    Delete a student by ID
----------------------------------------------------------------------

Author - Soumiyajit Das Chowdhury


























