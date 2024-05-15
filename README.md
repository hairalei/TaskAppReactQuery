# Task App

## Overview

This is a simple task management application consisting of a frontend and a backend server. The frontend is built using Vite and React, while the backend serves as the database for the application using local-server package. This is to practice the basics of **React Query**

## Setup Instructions

### Prerequisites

- Node.js (version 14 or above)
- npm (Node package manager)

### Downloading the Folders

1. Download the `app` folder for the frontend.
2. Download the `server` folder for the backend.

### Running the Server

1. Open the `server` folder in your code editor.
2. Run the following commands to install the necessary dependencies and start the local server:

   ```sh
   npm install
   npm run local-server
   ```

   This will set up the backend server which will act as the database for the task application.

### Running the Frontend

1. Open the app folder in your code editor.
2. Run the following commands to install the necessary dependencies and start the development server:

   ```sh
   npm install
   npm run dev
   ```

   This will start the frontend development server using Vite.

### About the Application

This task app allows you to:

- Create tasks
- Delete tasks
- Mark tasks as done/undone

### Learning Outcomes

In this project, I practiced using React Queries, specifically:

Implementing mutations and query clients.
Invalidating queries to keep the application in sync with the remote server.

### Conclusion

This project helped me understand how to effectively use React Queries to manage server state in a React application. The app provides basic functionality for managing tasks and ensures that the UI remains in sync with the backend data.
