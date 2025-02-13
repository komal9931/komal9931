# Zidio Task Management

## Overview
Zidio Task Management is a MERN stack-based task management system designed to streamline workflow by allowing users to assign tasks, set deadlines, track progress, and collaborate in real time. The system incorporates role-based permissions and secure authentication.

## Features
- **Task Assignment:** Assign tasks to team members with deadlines.
- **Deadline Tracking:** Monitor task deadlines and progress.
- **Progress Reporting:** Track the status of assigned tasks.
- **Role-Based Permissions:** Define roles such as Admin, Manager, and Employee with appropriate access.
- **Real-Time Collaboration:** Enable team members to communicate and work efficiently.
- **Secure Authentication:** Ensure security using JWT authentication.

## Tech Stack
- **Frontend:** React.js with Redux Toolkit & Tailwind CSS
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** JWT Authentication
- **Task UI Library:** AG Grid
- **Real-Time Features:** WebSockets (Socket.io)

## Installation

### Prerequisites
- Node.js (>=16.0)
- MongoDB installed and running

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/zidio-task-management.git
   cd zidio-task-management
   ```

2. **Install Dependencies**
   - Install backend dependencies:
     ```bash
     cd backend
     npm install
     ```
   - Install frontend dependencies:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up Environment Variables**
   - Create a `.env` file in the `backend` directory and add:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Run the Application**
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend application:
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application**
   Open your browser and navigate to `http://localhost:3000`

## API Endpoints

| Method | Endpoint            | Description |
|--------|---------------------|-------------|
| GET    | `/api/tasks`        | Fetch all tasks |
| POST   | `/api/tasks`        | Create a new task |
| PUT    | `/api/tasks/:id`    | Update task details |
| DELETE | `/api/tasks/:id`    | Delete a task |
| POST   | `/api/auth/login`   | User login |
| POST   | `/api/auth/register` | User registration |

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Added new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any queries or support, feel free to contact **Neha Kumari** at [your email].
