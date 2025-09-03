============================================================
            WORKSHOP BOOKING SYSTEM - DJANGO
============================================================

📌 Project Overview
-------------------
This is a Django-based Workshop Booking System that allows coordinators,
instructors, and users to manage, propose, and book workshops with ease. 
The system is designed with clean modular templates, Bootstrap styling, 
and extensible Django architecture.

Users can:
- Register, Login, and Logout.
- View available workshops.
- Propose new workshops.
- Accept or reject workshops based on role.
- Track workshop statuses in real-time.

------------------------------------------------------------
🚀 Features
------------------------------------------------------------
✅ User Authentication (Login, Logout, Signup)
✅ Role-based access control (Instructor, Coordinator, Participant)
✅ Workshop Proposal & Acceptance Flow
✅ Workshop Status Dashboard
✅ Pagination for workshop lists
✅ DatePicker integration for rescheduling
✅ Mobile-friendly, responsive UI with Bootstrap
✅ CSRF protection on all forms
✅ Error messages & success alerts
✅ Template inheritance for maintainable UI
✅ Custom Django template filters

------------------------------------------------------------
📂 Project Structure
------------------------------------------------------------
workshop_booking-master/
│
├── workshop_app/                # Main Django app
│   ├── templates/               # HTML templates
│   │   └── workshop_app/        # App-specific templates
│   │       ├── login.html
│   │       ├── base.html
│   │       ├── workshop_list.html
│   │       ├── workshop_status.html
│   │       └── ...
│   ├── static/                  # Static files (CSS, JS, Images)
│   ├── views.py                 # Core views
│   ├── models.py                # Database models
│   ├── urls.py                  # App URL routing
│   └── ...
│
├── workshop_booking/            # Project config
│   ├── settings.py              # Project settings
│   ├── urls.py                  # Global URL routing
│   └── ...
│
├── manage.py
└── requirements.txt             # Python dependencies

------------------------------------------------------------
⚙️ Installation & Setup
------------------------------------------------------------
1. Clone the repository
   git clone https://github.com/Debmalya2107/FOSSEE-Workshop_Booking.git
   cd workshop_booking

2. Create & activate a virtual environment
   python -m venv venv
   source venv/bin/activate        # For Linux/Mac
   venv\Scripts\activate           # For Windows

3. Install dependencies
   pip install -r requirements.txt

4. Apply migrations
   python manage.py makemigrations
   python manage.py migrate

5. Create superuser (admin access)
   python manage.py createsuperuser

6. Run the development server
   python manage.py runserver

7. Access the app in your browser:
   http://127.0.0.1:8000/

------------------------------------------------------------
📦 Dependencies
------------------------------------------------------------
- Django==3.0.7
- django-widget-tweaks (for form customization)
- Bootstrap (via CDN)
- jQuery & jQuery UI (datepicker support)

Install all with:
   pip install -r requirements.txt

------------------------------------------------------------
🔐 User Roles
------------------------------------------------------------
👤 Coordinator:
    - Propose workshops
    - Accept workshops
    - Update workshop details

👨‍🏫 Instructor:
    - View proposed workshops
    - Accept or reject based on availability

👥 User/Participant:
    - View available workshops
    - Register for workshops


------------------------------------------------------------
🤝 Contributing
------------------------------------------------------------
1. Fork the repo
2. Create a feature branch: git checkout -b feature-name
3. Commit changes: git commit -m "Add feature"
4. Push branch: git push origin feature-name
5. Open a Pull Request


============================================================
        🎉 Developed with Django + Bootstrap
============================================================
EOF
