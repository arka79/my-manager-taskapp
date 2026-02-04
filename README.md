# Task Manager App

A simple full-stack Task Manager application with user authentication, role-based access, and task management features. Users can register, log in, and manage their tasks, while admins can manage users.

---

## Features

- User registration and login
- Secure password hashing
- Role-based access (User / Admin)
- Create, read, update, and delete tasks
- Admin dashboard to manage users
- Protected routes using authentication
- Clean and simple UI

---

## Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- bcrypt for password hashing

### Frontend
- HTML
- CSS
- Vanilla JavaScript

---

## Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/arka79/my-manager-taskapp.git)
cd your-repo-name

2. Install dependencies
npm install

3. Setup environment variables

Create a .env file in the root directory:

PORT=3000
MONGO_URI=your_mongodb_connection_string


4. Start the server
node server.js

Using the App

Open auth.html to register or log in.

After login:

Users are redirected to dashboard.html

Admins are redirected to admin.html

Users can create, update, complete, and delete tasks.

Admins can view all users, change roles, and delete users.

Folder Structure
backend/
  routes/
  models/
  server.js

frontend/
  auth.html
  dashboard.html
  admin.html
  index.html
  styles.css
