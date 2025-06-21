# subject-notes-manager
Subject Notes Manager is a simple yet powerful web application built with Python Flask, Peewee ORM, and Bootstrap 5 that allows users to create, manage, edit, and delete notes categorized by subject.

This project is designed to help students, learners, and professionals organize their subject-wise notes effectively in one place with a clean and modern UI.

🔧 Features
🔐 User registration and login with session management
🧑‍🎓 Personalized avatars powered by DiceBear
✏️ Add, view, edit, and delete notes
📄 Responsive and user-friendly UI using Bootstrap
🔍 "Read more" and "Read less" for long notes
❗ Delete confirmation popups to avoid accidental removal
📱 Fully responsive design for mobile, tablet, and desktop

🛠️ Tech Stack
Python 3
Flask (Web Framework)
Peewee (Lightweight ORM)
SQLite (Database)
Bootstrap 5 via CDN
DiceBear Avatars API for user icons

📁 Folder Structure
📦 notes-manager/
 ┣ 📁 templates/          → HTML templates (login, register, dashboard, etc.)
 ┣ 📁 static/             → (Optional) CSS/JS files
 ┣ 📄 main.py             → Main Flask app entry point
 ┣ 📄 models.py           → Database models for User and Note
 ┣ 📄 auth.py             → Routes for login, register, logout
 ┣ 📄 operations.py       → Routes for dashboard, add/edit/delete notes
 ┣ 📄 requirements.txt    → List of dependencies
 ┗ 📄 README.md           → Project overview

🚀 How to Run
1. Clone the repository
git clone https://github.com/your-username/notes-manager.git
cd notes-manager

2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

3. Install dependencies
pip install -r requirements.txt

4. Run the Flask app
python main.py

💡 Why I Built This
This is my first full-stack Flask project, built to strengthen my understanding of backend logic, routing, templating with Jinja2, and responsive frontend design. It also marks the start of my journey on GitHub 🚀
