#  User Management System

A simple yet powerful Django-based User Management System with authentication, registration, and role-based access control. Built as part of my learning journey in Fullstack Web Development.

##  Features

- User Registration & Login
- Superuser/Admin Panel
- Role-based Access Control (Admin/User)
- Edit & Delete Users (Admin only)
- Password Hashing for Security
- Django Admin Dashboard
- Session Management
- Fully Responsive Frontend (HTML/CSS/Bootstrap)

##  Tech Stack

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default with Django)
- **Version Control:** Git & GitHub

##  Screenshots

> *(Add screenshots here if available)*  
> Example: Registration Page, Login Page, Admin Panel, User List Table
 
##  Installation 

Follow these steps to run the project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/user-management.git
cd user-management

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate<img width="1909" height="906" alt="Screenshot 2025-07-23 144159" src="https://github.com/user-attachments/assets/deb71d9a-ce4a-48e7-a9f8-5ecca657aff0" />


# Create a superuser (follow the prompts)
python manage.py createsuperuser

# Run the development server
python manage.py runserver
