# TaskManager Pro

**TaskManager Pro** is a web application designed to streamline task management and enhance team collaboration. It features secure user authentication, task tracking, task assignment, and email notifications to ensure productivity and timely completion of tasks.

## Features

- **User Authentication**: Secure sign-up, login, and password recovery using JWT authentication.
- **Task Management**: Create, read, update, and delete tasks (CRUD operations).
- **Team Collaboration**: Share and assign tasks to team members.
- **Email Notifications**: Receive updates and reminders for task deadlines.
- **Scalable**: Built using React.js, Node.js, MongoDB, and JWT for performance and scalability.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js (Express)
- **Database**: MongoDB
- **Cloud**: AWS S3/EC2
- **Authentication**: JWT (JSON Web Token)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/taskmanager-pro.git

2. Install dependencies for the backend:

bash
Copy
Edit
cd taskmanager-pro/backend
npm install
3. Install dependencies for the frontend:

bash
Copy
Edit
cd taskmanager-pro/frontend
npm install
4. Set up environment variables:

Create a .env file in the backend directory with the following:
env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Start the backend server:

bash
Copy
Edit
cd taskmanager-pro/backend
npm start
5. Start the frontend server:

bash
Copy
Edit
cd taskmanager-pro/frontend
npm start
Usage
Sign Up: Register a new account with your username, email, and password.
Login: Log in to your account to access your tasks.
Create Tasks: Add new tasks with titles, descriptions, due dates, and assignees.
Assign Tasks: Assign tasks to team members for collaboration.
Receive Notifications: Get email alerts for task updates and deadlines.
