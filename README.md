# Task_Manager_Web_Application

**Description**

This is a Task Manager web application that allows users to create, view, update, and delete tasks. The application is designed with frontend, backend, database, and API components, enabling users to register, log in, and effectively manage their tasks.

Features

- **User Authentication**: Users can register and log in securely with password hashing and JWT-based authentication.
- **Task Management**: Users can perform CRUD operations (Create, Read, Update, Delete) on tasks.
- **Responsive Design**: The frontend is intuitive and mobile-friendly for different screen sizes.
- **Backend**: Efficiently handles API requests, validation, and task management operations.
- **Database Integration**: Stores user and task data securely in the database.
- **Error Handling**: Meaningful error messages and robust validation for a smooth user experience.

**Project Structure**

Backend Development

1. **Server Setup**:
   - Built using **Node.js** and **Express.js**.
   - JWT is used for user authentication and authorization.
2. **API Endpoints**:
   - User Registration: `/api/auth/register`
   - User Login: `/api/auth/login`
   - Task Management: `/api/tasks` (Create, Read, Update, Delete)
3. **Validation and Error Handling**:
   - Input validation is implemented to ensure proper API usage.
   - Error messages are provided for meaningful feedback.
     
Database Setup

1. **Database Choice**:
   - **MongoDB** was chosen for this project.
2. **Database Schema**:
   - User Schema: Stores user information (e.g., username, email, password).
   - Task Schema: Stores task information (e.g., title, description, status, due date, user ID).
     
Frontend Development

1. **Framework**:
   - Built with **React.js** for a responsive and user-friendly interface.
2. **Components**:
   - **Auth**: Login and Registration forms.
   - **Task Management**: Pages for displaying, adding, editing, and deleting tasks.
3. **Styling**:
   - CSS is used for responsive design and an intuitive interface.
     
Integration

1. The frontend communicates with the backend using RESTful APIs.
2. User authentication is implemented to secure access to task management features.
   
Setup and Installation

Requirements

- Node.js
- MongoDB
- npm (Node Package Manager)
  
**Steps to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/GeetaChauhan777/Task_Manager_Web_Application.git
   ```
2. Navigate to the task-manager-web-app directory:
   ```bash
   cd task-manager-web-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the root of the backend directory and add the following variables:
   ```env
   DB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```
5. Start the React development server:
   ```bash
   npm run dev
   ```
   
Live Demo

The application is hosted live on a **Netlify** platform. [Demo Link](https://taskmanagerwebapplication.netlify.app/)

Testing

- **Unit Testing**:
  - Backend API testing is performed using tools like Postman.
  - Unit tests for frontend components can be added.
- **Manual Testing**:
  - Test all functionalities, including edge cases (e.g., invalid input, unauthorized access).
    
Acceptance Criteria

- **Functionality**: Users can register, log in, and perform CRUD operations on tasks.
- **User Interface**: The design is responsive and visually appealing.
- **Backend Implementation**: Efficient API handling with authentication and task operations.
- **Database Integration**: Properly stores user and task data securely.
- **Security**: Input validation, password hashing, and JWT implementation.
- **Error Handling**: Meaningful error messages are provided.

  **Demo Video**

https://github.com/user-attachments/assets/9d0b9fa9-a711-41e5-93fc-033ad978b640

**Sample User Logins :**

1.	Employee Login:
   
•	Email : employee1@gmail.com

•	Password : Password@123

2.	Customer Login :
   
•	Email : customer1@gmail.com

•	Password : Password@123
