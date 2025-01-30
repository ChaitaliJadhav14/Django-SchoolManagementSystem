## 🎓 Django School Management System
Developed a School Management System using Django to streamline academic and administrative operations. The system supports role-based access for administrators, teachers, students, and parents, ensuring secure data management.

## 🛠 Technologies Used:
   Backend: Python (Django), Django REST Framework
   Frontend: HTML, CSS, JavaScript (Django Templates)
   Database: SQLite
   Version Control & Deployment: Git, Shell Scripting .
   
## 🚀 Project Features:
   1. User Authentication & Role-Based Access – Secure login for different users (Admin, Teacher, Student, Parent).
   2. Student Management – Maintain student records, attendance, and grades.
   3. Fee & Finance Management – Track fee payments and generate invoices.
   4. Timetable & Scheduling – Teachers and students can view and manage class schedules.
   5. Performance Analytics – Generate reports for student progress and administrative insights.
   6. Secure & Scalable – Follows Django’s security best practices and can be extended with RESTful APIs.
      
## 📥 Installation 
   #### Create a Virtual Environment & Install Dependencies
        python -m venv venv
        source venv/bin/activate  # Windows: venv\Scripts\activate
        pip install -r requirements.txt
  #### Apply Migrations & Create Superuser
       python manage.py migrate
       python manage.py createsuperuser
  #### Run the Development Server
       python manage.py runserver
       
## 🔗 Access the application at http://127.0.0.1:8000/

#### 🎮 Usage
  1️⃣ Admin Dashboard: http://127.0.0.1:8000/admin/ (Login with superuser credentials)
  2️⃣ Student Portal: View grades, assignments, and attendance
  3️⃣ Teacher Portal: Manage class records, assignments, and schedules
  
#### 🔒 Security Considerations
    Use .env file to store sensitive information (e.g., database credentials).
    Change the default /admin/ route for security reasons.
    Enable Django security settings (SECURE_SSL_REDIRECT = True).
