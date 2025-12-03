📚 Library Management System (LMS)

A complete Library Management System built using Flask (Python) with a modern frontend using HTML, CSS, and JavaScript.
This system allows admins and students to manage library operations such as adding books, issuing/returning books, and viewing records.

🚀 Features
🔐 Authentication

Admin Login

Student Login

Role-based navigation

📘 Book Management

Add New Books

Issue Books

Return Books

View All Books

View Issued & Returned Books

👨‍🎓 Student Management

Add/Register Students

View Student List

Student Login Page

🖥️ User Interface

Clean, modern, responsive pages

Built using HTML, CSS (static/style.css), JavaScript (static/app.js)

Jinja2 templates for Flask integration

🛠️ Tech Stack
Backend

Python Flask

Jinja2 Templates

Simple Routing System

Frontend

HTML5

CSS3

JavaScript


LMS/
│── app.py
│── .gitignore
│
├── static/
│   ├── style.css
│   └── app.js
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── student_login.html
│   ├── dashboard.html
│   ├── selection.html
│   ├── add_book.html
│   ├── add_student.html
│   ├── issue_book.html
│   ├── return_book.html
│   ├── view_books.html
│   ├── view_students.html
│   ├── issued_returned_books.html
│
└── README.md


⚙️ Installation & Setup
1️⃣ Create Virtual Environment - python -m venv venv
2️⃣ Activate Virtual Environment - venv\Scripts\activate
3️⃣ Install Dependencies - pip install flask
4️⃣ Run the Application - python app.py
5️⃣ Open in Browser - http://127.0.0.1:5000/

▶️ How the System Works

When the app starts, the user lands on selection.html

Users can choose Admin or Student

Admin can:

Add books

Add students

Issue & return books

View books and student list

Manage overall library operations

Students can:

Log in

Browse books

View personal issued books (if enabled)

All pages route through Flask using render_template().
