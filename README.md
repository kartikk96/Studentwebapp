🎓 Student Counseling Web Application

📌 Project Overview

The Student Counseling Web Application is a web-based platform designed to simplify and automate the student admission and counseling process. It helps students apply for admission, submit their academic details, select their preferred courses, and track their application status.

The system automatically ranks students based on their academic performance and assists administrators in allocating seats according to student ranks, course preferences, and seat availability.

The main objective of this project is to reduce manual work, save time, minimize human errors, and make the admission process more efficient and transparent.

🚀 Key Features

👨‍🎓 Student Module

- Student Registration and Login.
- Secure Authentication.
- Student Profile Management.
- Submission of Academic Details.
- Course and Branch Preference Selection.
- Online Payment Proof Upload.
- Application Status Tracking.
- Download Admission Offer Letter in PDF Format.

🛠️ Admin Module

- Secure Admin Login.
- Manage Student Applications.
- View and Manage Student Records.
- Verify Payment Receipts.
- Automatically Rank Students Based on Academic Marks.
- Manage Course Preferences.
- Allocate Seats Based on Rank and Seat Availability.
- Generate PDF Offer Letters for Selected Students.

⚙️ Technologies Used

Technology| Purpose
HTML5| Website Structure
CSS3| Styling and Layout
Bootstrap| Responsive UI
JavaScript| Frontend Interactivity
Python| Backend Programming
Django| Web Framework
SQLITE| Database Management
Django Authentication| User Authentication

🔄 Working Process

1. Registration: Students create an account and log in to the application.
2. Academic Details: Students enter their educational qualifications and marks.
3. Course Selection: Students select their preferred courses or branches.
4. Payment Submission: Students upload their payment receipt.
5. Ranking: The system calculates academic scores and generates student rankings.
6. Verification: The administrator verifies student details and payment receipts.
7. Seat Allocation: Seats are allocated according to student rank, preferences, and availability.
8. Offer Letter: After successful verification and allocation, the system generates an admission offer letter in PDF format.

🗂️ Project Structure

Student-Counseling-Web-Application/
│
├── manage.py
├── db.sqlite3
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── app/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── admin.py
│
├── media/
│   └── payment_receipts/
│
└── requirements.txt

Note: Adjust the folder and database names according to your actual project structure.

💻 Installation and Setup

1. Clone the Repository

git clone <your-repository-url>

2. Navigate to the Project Directory

cd Student-Counseling-Web-Application

3. Create a Virtual Environment

python -m venv venv

4. Activate Virtual Environment

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate

5. Install Dependencies

pip install -r requirements.txt

6. Apply Database Migrations

python manage.py makemigrations
python manage.py migrate

7. Create Admin Account

python manage.py createsuperuser

8. Run the Development Server

python manage.py runserver

Open your browser and visit:

http://127.0.0.1:8000/

🔐 Security Features

- User authentication and authorization.
- Separate student and administrator interfaces.
- Form validation for student information.
- Protected administrative operations.
- Secure handling of application records.

🎯 Project Objectives

- Automate the traditional student counseling process.
- Reduce paperwork and manual efforts.
- Improve transparency in admission procedures.
- Provide an efficient student ranking mechanism.
- Simplify payment verification and seat allocation.
- Generate digital admission offer letters.

🔮 Future Enhancements

- Online payment gateway integration.
- Email and SMS notifications.
- Real-time application tracking.
- Advanced analytics dashboard.
- Cloud deployment and online accessibility.
- AI-based course recommendation system.

👨‍💻 Developer

Kartik Kanojia

B.Tech – Computer Science and Engineering

Birla Institute of Applied Science

Areas of Interest: Java Development | Full-Stack Development | Python | Web Technologies

---

⭐ If you find this project useful, consider giving it a star!

Made with ❤️ to simplify the student admission and counseling process.
