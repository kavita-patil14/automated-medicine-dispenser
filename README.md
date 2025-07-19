# 💊 Automated Medicine Dispenser Box using IoT

This is a smart web-based and IoT-integrated solution that helps users manage their daily medication routines. The system allows users to schedule, dispense, and track their medicine intake with real-time notifications, reminders, and reports.

---

## 🧠 Overview

This system is ideal for both independent users and those with caretakers. It helps anyone — especially elderly patients or individuals with busy routines — stay on track with their medication through timely reminders and automatic dispensing.

---

## 🚀 Features

### 🧑‍⚕️ User Management
- User registration and login
- Admin dashboard to view stats and control features
- Profile editing and password management

### 📋 Patient Management
- Create, update, and delete patient records
- View patient list with details

### 💊 Prescription Management
- Add prescriptions with dosage, timing, and instructions
- Email alerts for medicine refill reminders (to the user or caretaker if available)  
- Allows patients to manage their own medication or involve caretakers through optional email alerts

### 📅 Appointment Scheduling
- Schedule appointments
- View, update, and delete appointments

### 📈 Medication Monitoring
- Medicine consumed history
- Visual graphs showing medication patterns

### 🔔 Notifications
- Admin can send notifications to users
- Users can view their notifications dashboard

### 📬 Contact & Feedback
- Contact form to reach admin/support
- Option to leave reviews and feedback

### 📡 IoT Integration
- Arduino-based automated dispenser
- Serial communication with Django to trigger dispensing
- Real-time tracking and alerts using hardware

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Python, Django
- **Database:** SQLite
- **Hardware:** Arduino UNO, Motor Driver, IR Sensor, Motor, LED, Buzzer, Pill Container, LiPo Battery, Jumper Wires. 
- **Email:** Django's EmailMessage
- **Tools:** Visual Studio Code, PyCharm, Git, GitHub

---

## 📂 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/automated-medicine-dispenser.git
cd automated-medicine-dispenser
