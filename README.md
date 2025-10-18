🎓 Django Student Management System

This is a Student Management System developed using Python (Django Framework).
It is a full-featured web application designed to help educational institutions manage students, staff, courses, subjects, attendance, results, and leave requests efficiently — all from a single platform.

This project demonstrates core Django development skills, including model–view–template (MVT) architecture, database handling, authentication, and role-based dashboards.

## 🎥 Demo Video

👉 Watch the full demo here:  
[![Watch the demo][https://drive.google.com/file/d/15kSAc44sJhd4_nCj89EyKYtLiYpHWH1s/view?usp=sharing
]

🚀 Features
🧑‍💼 Admin Panel

View summarized dashboards and performance charts of students and staff.

Manage students, staff, courses, subjects, and sessions (add, update, delete).

Review and manage attendance records.

Approve or reject leave requests from staff and students.

Review and respond to feedback messages.

👨‍🏫 Staff/Teacher Panel

View dashboard analytics for their assigned subjects and students.

Take and update attendance.

Add or edit student results.

Apply for leave and send feedback to the admin.

👨‍🎓 Student Panel

View personalized dashboards showing attendance, subjects, and results.

Apply for leave and submit feedback.

View overall performance reports and attendance summaries.

🧰 Tech Stack

Framework: Django (Python)

Frontend: HTML5, CSS3, JavaScript, Bootstrap

Database: SQLite3 (default)

Libraries: Django ORM, Chart.js (for graphs & data visualization)

Server: Django Development Server (run via manage.py)

⚙️ Installation and Setup
✅ Pre-requisites

Ensure the following are installed on your system:

Python (latest version)

Pip (Python Package Manager)

Git Version Control

🧩 Step 1: Clone the Repository
git clone https://github.com/kapilkushwaha/student-management-system.git
cd student-management-system

🧱 Step 2: Create a Virtual Environment

Windows:

python -m venv venv
venv\Scripts\activate


Mac/Linux:

python3 -m venv venv
source venv/bin/activate

📦 Step 3: Install Required Dependencies
pip install -r requirements.txt

⚙️ Step 4: Configure Allowed Hosts

In settings.py, update:

ALLOWED_HOSTS = ['*']

▶️ Step 5: Run the Server

Windows:

python manage.py runserver


Mac/Linux:

python3 manage.py runserver


Now open your browser and go to:

http://127.0.0.1:8000/

🔐 Step 6: Login Credentials

Create Superuser (Admin):

python manage.py createsuperuser


Then add your admin email, username, and password.

Example Roles:

Role	Email	Password
Admin (HOD)	admin@gmail.com
	admin
Staff	staff@gmail.com
	staff
Student	student@gmail.com
	student
📊 Future Enhancements

Email notifications for leave approvals and results.

Attendance and performance export (Excel/PDF).

Integration of AI-based performance prediction module.

Mobile-friendly responsive dashboard.

👨‍💻 Developer

Developed by: Kapil Kushwaha
Field of Expertise: Python | Django | Data Analytics | Visualization Tools
LinkedIn: [linkedin.com/in/kapilkushwaha](https://www.linkedin.com/in/kapil-kushwaha-a08b03263/)

GitHub: [github.com/kapilkushwaha](https://github.com/Kapil-Kushwaha)

⭐ About This Project

This project was designed and implemented from scratch using Django for demonstration and educational purposes.
It serves as a practical example of building a complete role-based management system with database integration, form handling, and data visualization.