# 🎓 Student Management System

The **Student Management System** is a web app for managing student records with features to add, edit, view, and delete student data, using a **MySQL database** and responsive design.

---
### Step 2: Initialize the project

Now, let's set up the project files.

1. Open a terminial and create a new project directory:

   ```bash
   mkdir student-management
   cd student-management
   ```
2. Initialize a new Node.js project by running:
 ```bash
  npm init -y
```
3. Install the required dependencies:
 ```bash
npm install express mysql

npm install cors
```
4. To start Express server
   ```bash
   node server.js
   ```
#### node server.js is how you launch your backend server to make your web app run locally. Without this, the server-side (API, database handling, etc.) won’t work.

## You are telling Node.js to execute your server.js file, which:

Starts your Express server.

Listens for HTTP requests on a port (like 3000 or 5500).

Handles all the backend functionality — like:

Getting data from the MySQL database,

Inserting new records,

Updating or deleting student information,

Serving your frontend files (index.html, CSS, JS, etc.).  
## ✨ Features

- 📥 Add new student records
- ✏️ Edit existing student information
- 👀 View student details in a structured table
- 🗑️ Delete student records
- 🔄 Responsive UI for better user experience
- 🔐 Backend integration with MySQL for secure data handling

---

## 💻 Technologies Used

### 🖥️ Frontend
- HTML5  
- CSS3  
- JavaScript (Vanilla)  
- Fetch API  

### 🗄️ Backend
- Node.js  
- Express.js  
- MySQL  
- MySQL Workbench  

### 🧰 Tools & Middleware
- Body-Parser - Middleware to parse incoming request bodies in Express 
- CORS  - Middleware to handle Cross-Origin Resource Sharing
- Git & GitHub   

---

## 🏁 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Gauravkumar1741/student_management_workbench.git

![image alt](https://github.com/Gauravkumar1741/student_management_workbench/blob/b92f537acffe509cd23e01b36ec1c5ed8193a7eb/first_page.png)
   
