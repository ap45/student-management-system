Here’s a simplified and unique version of the `README.md` for the Student Management System built with Django:

---

# Student Management System Using Django

This project is a **simple Student Management System** developed while learning Django. It includes multiple user types (Admin, Staff, and Student) with various functionalities for each. The system is designed to help manage student records, courses, attendance, and feedback seamlessly.

## Features

### Admin Features
- View summary charts for student performance, staff performance, courses, subjects, and more.
- Manage staff, students, courses, and subjects (Add, Update, Delete).
- Review and respond to feedback and leave applications.
- Monitor student attendance and manage academic sessions.

### Staff/Teacher Features
- View summary charts related to students and subjects.
- Take and update student attendance.
- Add and update results.
- Apply for leave and send feedback to the Head of Department (HOD).

### Student Features
- View attendance records and academic results.
- Apply for leave and send feedback to the HOD.

**Login Credentials:**  
- Admin: `admin@admin.com` | Password: `admin`  
- Staff: `staff@staff.com` | Password: `staff`  
- Student: `student@student.com` | Password: `student`


## How to Install and Run the Project

### Prerequisites

Before you begin, make sure you have the following installed:
- [Git](https://git-scm.com/)
- [Python](https://www.python.org/downloads/)
- [Pip](https://pip.pypa.io/en/stable/installing/)

### Installation Steps

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/jobic10/student-management-using-django.git
   cd student-management-using-django
   ```

2. **Create a Virtual Environment**  
   For Windows:
   ```bash
   python -m venv venv
   source venv/scripts/activate
   ```
   For Mac/Linux:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Allowed Hosts**  
   Open `settings.py` and set your allowed hosts:
   ```python
   ALLOWED_HOSTS = []
   ```

5. **Run the Application**  
   For Windows:
   ```bash
   python manage.py runserver
   ```
   For Mac/Linux:
   ```bash
   python3 manage.py runserver
   ```

6. **Create Superuser**  
   Create an admin account by running:
   ```bash
   python manage.py createsuperuser
   ```

## Contributions

Feel free to modify and enhance the project to suit your needs. If you like this project, consider **adding a star ⭐️** on GitHub!

## References

Helpful resources used during development:
- [Django Documentation](https://docs.djangoproject.com/en/4.0/)
- [Stack Overflow Discussions](https://stackoverflow.com/questions/tagged/django)
- [SimpleIsBetterThanComplex](https://simpleisbetterthancomplex.com/)
