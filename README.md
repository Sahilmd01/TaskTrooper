<h2>TaskTrooper - Task Management Application</h2> 

<p>TaskTrooper is a MERN stack-based task management application that supports both admin and user logins, with different priority levels for tasks (Normal, Medium, High). Admins can manage tasks, while users can manage their own tasks and progress.</p>

<h3>🎮 Features</h3>
<ul>
  <li><strong>Admin Login</strong>: Admins can manage all tasks, assign priorities, and oversee user activities.</li>
  <li><strong>User Login</strong>: Users can log in and track their own tasks based on priorities.</li>
  <li><strong>Task Prioritization</strong>: Tasks can be categorized as Normal, Medium, or High priority.</li>
  <li><strong>Task Management</strong>: Admins can create, edit, and delete tasks.</li>
  <li><strong>User Dashboard</strong>: Users have access to their own task lists, organized by priority.</li>
</ul>

<h3>🛠️ Installation</h3>
<p>Make sure you have <strong>Node.js</strong> and <strong>MongoDB</strong> installed on your machine. Then, follow these steps to set up the project:</p>

<pre><code>1. Clone the repository:
   git clone https://github.com/yourusername/TaskTrooper.git
   cd TaskTrooper

2. Install backend dependencies:
   cd backend
   npm install

3. Install frontend dependencies:
   cd frontend
   npm install

4. Create a .env file in the backend directory and set the following variables:
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
</code></pre>

<h3>▶️ How to run</h3>
<pre><code>1. Start the backend server:
   cd backend
   npm start

2. Start the frontend server:
   cd frontend
   npm start

3. Access the app in your browser at http://localhost:3000.</code></pre>

<h3>🖥️ Controls</h3>
<table>
  <tr>
    <th>Key</th>
    <th>Action</th>
  </tr>
  <tr>
    <td><strong>Admin Login</strong></td>
    <td>Log in as an admin</td>
  </tr>
  <tr>
    <td><strong>User Login</strong></td>
    <td>Log in as a regular user</td>
  </tr>
  <tr>
    <td><strong>Create Task</strong></td>
    <td>Admin can create new tasks</td>
  </tr>
  <tr>
    <td><strong>Update Task</strong></td>
    <td>Users can update their tasks</td>
  </tr>
  <tr>
    <td><strong>Assign Priority</strong></td>
    <td>Admins can assign task priorities</td>
  </tr>
</table>

<h3>📂 File Structure</h3>
<pre><code>TaskTrooper/
├── backend/         # Backend server code (Express, MongoDB)
│   ├── controllers/ # Handles API requests
│   ├── models/      # Mongoose models for MongoDB
│   ├── routes/      # API routes
│   └── server.js    # Backend server setup
├── frontend/        # Frontend code (React)
│   ├── components/  # React components
│   └── App.js       # Main frontend application
├── .env             # Environment variables
├── README.md        # Project documentation
</code></pre>

<h3>🚀 Future Improvements</h3>
<ul>
  <li>Implement notifications for task deadlines.</li>
  <li>Integrate email reminders for users.</li>
  <li>Add advanced task filtering and sorting.</li>
  <li>Enable task sharing between users.</li>
</ul>

<h3>📜 License</h3>
<p>This project is open-source and licensed under the MIT License.</p>

<hr>

<p>Enjoy using TaskTrooper! 📋🚀</p>

>
