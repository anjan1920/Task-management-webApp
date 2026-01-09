

## **Full-Stack Task Management System (MERN)**

### **Overview**

A cloud-based task management web application that enables teams to create, assign, and track tasks with **role-based access control** for admins and regular users.

---

### **Problem**

Manual task tracking using spreadsheets or chat tools lacks visibility, accountability, and access control, especially for remote or distributed teams.

---

### **Solution**

Developed a **full-stack MERN application** that centralizes task management, enforces role-based permissions, and provides real-time task status tracking.

---

### **Technologies**

* **Frontend:** React (Vite), Redux Toolkit, Tailwind CSS, Headless UI
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Auth:** JWT-based authentication & authorization

---

### **Core Features**

#### **Admin**

* Create and manage user accounts
* Assign tasks to individual or multiple users
* Update task status, priority, and subtasks
* Upload and manage task-related assets
* Disable or delete users and tasks

#### **Users**

* View assigned tasks and task details
* Update task status (todo → in progress → completed)
* Add comments for task-level collaboration

#### **General**

* JWT-based secure authentication
* Role-based access control (admin vs user)
* User profile and password management
* Dashboard with task filtering and summaries

---

### **How It Works**

* React frontend communicates with Express backend via REST APIs
* JWT tokens secure protected routes and admin-only operations
* MongoDB stores users, tasks, priorities, and subtasks
* Redux Toolkit manages global state for tasks and authentication

---

### **Challenges & Learnings**

* Implemented **role-based authorization** to restrict admin-only operations
* Designed scalable MongoDB schemas for tasks and subtasks
* Managed complex global state using Redux Toolkit
* Improved UI responsiveness and accessibility using Tailwind CSS and Headless UI

---

### **Run Locally**

1. Clone the repository
2. Install frontend and backend dependencies
3. Configure environment variables
4. Start backend and frontend servers


