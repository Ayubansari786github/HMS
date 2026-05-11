# 🏥 Hospital Management System

A web-based Hospital Management System built using **Python** and **Django**.

This project helps manage hospital operations digitally by handling:

* Doctors
* Patients
* Appointments
* Admin Management
* Contact Queries

---

# 🚀 Features

## 👨‍⚕️ Doctor Management

* Add Doctor
* Update Doctor Details
* Delete Doctor
* View Doctor List

## 🧑‍🤝‍🧑 Patient Management

* Add Patient
* Update Patient Details
* Delete Patient
* View Patient List

## 📅 Appointment Management

* Create Appointments
* Manage Appointment Records
* Connect Doctors & Patients

## 🔐 Authentication

* Admin Login
* Secure Authentication using Django

## 📊 Dashboard

* Total Doctors
* Total Patients
* Total Appointments

---

# 🛠️ Tech Stack

* Python
* Django
* SQLite
* HTML
* CSS
* Bootstrap

---

# 📂 Project Structure

```bash
HospitalManagementSystem/
│
├── manage.py
├── db.sqlite3
│
├── HospitalManagementSystem/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
└── hospitals/
    ├── models.py
    ├── views.py
    ├── admin.py
    ├── templates/
    └── static/
```

---

# ⚙️ How To Run The Project

## Step 1: Clone the Repository

```bash
git clone https://github.com/ayubansari/HospitalManagementSystem.git
```

---

## Step 2: Open Project Folder

```bash
cd HospitalManagementSystem
```

---

## Step 3: Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Step 4: Install Dependencies

```bash
pip install django
```

---

## Step 5: Run Database Migrations

```bash
python manage.py migrate
```

---

## Step 6: Create Superuser

```bash
python manage.py createsuperuser
```

Enter:

* Username
* Email
* Password

---

## Step 7: Start Development Server

```bash
python manage.py runserver
```

---

# 🌐 Open In Browser

```bash
http://127.0.0.1:8000/
```

---

# 🔑 Admin Panel

```bash
http://127.0.0.1:8000/admin
```

Login using the superuser credentials created earlier.

---

# 🧠 Project Architecture

This project follows Django’s MVT Architecture:

* Model → Database Logic
* View → Business Logic
* Template → Frontend UI

---

# 📌 Future Improvements

* Role-Based Authentication
* REST API Integration
* React Frontend
* Email Notifications
* Better UI/UX
* Cloud Deployment

---

# 📷 Project Demo

Add screenshots or Loom video link here.

---

# 👨‍💻 Developer

**Ayub Ansari**

---

# ⭐ Conclusion

This project helped improve understanding of:

* Django Framework
* CRUD Operations
* Authentication
* Database Relationships
* Backend Development
* Web Application Structure
