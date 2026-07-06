# 🏥 Hospital Management System (HMS)

A comprehensive web-based Hospital Management System developed using **Django** to streamline hospital operations by providing dedicated portals for **Administrators**, **Doctors**, and **Patients**. The system digitizes hospital workflows such as appointment scheduling, patient record management, doctor administration, and medical history tracking, ensuring secure, efficient, and organized healthcare management.

---

# 📖 Table of Contents

- About the Project
- Problem Statement
- Objectives
- Features
- Modules
- System Workflow
- Technology Stack
- Project Structure
- Installation
- Future Enhancements
- Author

---

# 📌 About the Project

Hospital Management System (HMS) is designed to simplify the daily operations of hospitals by replacing traditional paper-based record keeping with a centralized digital platform.

The application enables patients to register, schedule appointments, consult doctors, and access their medical information. Doctors can efficiently manage appointments, review patient histories, and prescribe treatments, while administrators oversee the entire system, including doctors, patients, appointments, and hospital records.

The system improves operational efficiency, minimizes manual errors, enhances communication among stakeholders, and ensures secure management of healthcare information.

---

# ❗ Problem Statement

Managing hospital operations manually presents several challenges:

- Maintaining paper-based patient records
- Time-consuming appointment scheduling
- Difficulty in tracking patient history
- Inefficient communication between doctors and patients
- Increased administrative workload
- Higher chances of data redundancy and human errors

This Hospital Management System addresses these challenges by providing an integrated digital platform for hospital management.

---

# 🎯 Objectives

The project aims to:

- Digitize hospital management processes.
- Simplify patient registration and appointment booking.
- Provide secure storage of patient medical records.
- Improve communication between doctors and patients.
- Reduce paperwork and administrative effort.
- Ensure efficient management of hospital resources.
- Provide role-based access for administrators, doctors, and patients.

---

# ✨ Features

## 🔐 User Authentication

- Secure Login
- User Registration
- Role-Based Access Control
- Session Management

---

## 👨‍💼 Admin Module

The administrator has complete control over the application.

Responsibilities include:

- Manage doctors
- Manage patients
- Approve appointments
- Update hospital information
- View system statistics
- Monitor hospital activities
- Maintain records

---

## 👨‍⚕️ Doctor Module

Doctors can perform the following tasks:

- Login securely
- View scheduled appointments
- Access patient details
- Review medical history
- Update diagnoses
- Prescribe medications
- Maintain treatment records

---

## 👩 Patient Module

Patients can:

- Register online
- Login securely
- Book appointments
- View appointment status
- Browse available doctors
- Access medical records
- View prescriptions

---

## 📅 Appointment Management

The appointment management system allows patients to schedule consultations online.

Key functionalities include:

- Appointment Booking
- Appointment Approval
- Appointment Cancellation
- Appointment Tracking
- Doctor Availability Management

---

## 📁 Patient Record Management

The system securely stores:

- Personal Information
- Contact Details
- Medical History
- Diagnosis Reports
- Prescriptions
- Treatment Plans
- Appointment History

---

## 📊 Dashboard

Each user is provided with a dedicated dashboard displaying relevant information.

### Admin Dashboard

- Total Doctors
- Total Patients
- Total Appointments
- Pending Requests
- System Statistics

### Doctor Dashboard

- Today's Appointments
- Assigned Patients
- Recent Prescriptions
- Treatment History

### Patient Dashboard

- Upcoming Appointments
- Medical History
- Prescriptions
- Doctor Information

---

# ⚙️ System Workflow

1. The patient registers and creates an account.
2. The patient logs into the system.
3. The patient books an appointment with an available doctor.
4. The administrator manages and verifies hospital records.
5. The doctor reviews appointment requests.
6. The doctor consults the patient and records the diagnosis.
7. Prescriptions and treatment details are stored in the database.
8. Patients can access their appointment history and medical records at any time.

---

# 🛠️ Technology Stack

## Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

## Backend

- Python
- Django Framework

## Database

- SQLite

## Development Tools

- Visual Studio Code
- Git
- GitHub

---

# 📂 Project Structure

```
Hospital-Management-System/
│
├── hospital/
├── doctor/
├── patient/
├── templates/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

---

# 🚀 Installation Guide

## Clone the Repository

```bash
git clone https://github.com/yourusername/Hospital-Management-System.git
```

## Navigate to the Project Directory

```bash
cd Hospital-Management-System
```

## Create a Virtual Environment

```bash
python -m venv venv
```

## Activate the Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

## Start the Development Server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

---

# 🔮 Future Enhancements

The project can be further enhanced by integrating:

- Online video consultations
- AI-powered medical chatbot
- Electronic Health Record (EHR) integration
- Online payment gateway
- Pharmacy management
- Laboratory management
- SMS and email notifications
- Medical report downloads
- Cloud deployment
- Mobile application support

---

# 📚 Learning Outcomes

Through this project, the following concepts were implemented:

- Django Framework
- MVC/MVT Architecture
- Authentication & Authorization
- CRUD Operations
- Database Management
- URL Routing
- Template Rendering
- Form Validation
- Session Management
- Responsive Web Design
- Role-Based Access Control

---

# 👨‍💻 Author

**Khushi Gowda**

Python Full Stack Developer | Django Developer | AI & Machine Learning Enthusiast

---

# 📄 License

This project is developed for educational and learning purposes. It demonstrates the implementation of a complete Hospital Management System using the Django framework.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
