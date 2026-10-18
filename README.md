# 📡 StudentSync – Smart Student Attendance Monitoring System

StudentSync is a smart attendance monitoring system that automates student attendance using GPS geofencing and location-based verification. The project provides dedicated interfaces for students, parents, and administrators to improve attendance management and monitoring.

> **Project status:** StudentSync is a frontend prototype. It runs entirely in the browser with no backend: users, attendance records, notifications and geofence settings are saved in the browser's LocalStorage, and sign-in is checked in client-side JavaScript against demo accounts. Data is therefore not shared between devices, and the parent dashboard shows alerts generated in the same browser, not live data from a student's phone. The geofencing uses the browser Geolocation API with a configurable campus location and radius (500 m by default).

## 🚀 Features

- 📍 GPS-based Geofencing for attendance verification
- 🎓 Student Dashboard
- 👨‍👩‍👧 Parent Dashboard with campus entry/exit and attendance alerts
- ⚙️ Admin Dashboard for student and timetable management
- 📊 Attendance Analytics
- 🔔 In-app Notifications
- 📅 Timetable Management
- 🔐 Role-based Login System
- 📱 Responsive UI

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- LocalStorage (Demo Data)
- Geolocation API

## 📂 Project Structure

```
studentsync/
│── index.html
│── about.html
│── login.html
│── register.html
│── parent-dashboard.html
│── admin-dashboard.html
│── student-dashboard.html
│── script.js
└── style.css
```

## 👥 User Roles

### Student
- Login/Register
- View Attendance
- Check Timetable
- GPS Location Tracking
- Attendance Analytics

### Parent
- Monitor Student Status
- Receive Attendance Alerts
- View Timetable
- Track Campus Entry & Exit

### Admin
- Manage Students
- Manage Timetable
- Configure Geofence
- View Analytics
- Monitor Attendance Records

## 🔑 Demo Credentials

### Student
- **Email:** `student@demo.com`
- **Password:** `demo123`

### Parent
- **Email:** `parent@demo.com`
- **Password:** `demo123`

### Admin
- **Email:** `admin@demo.com`
- **Password:** `demo123`

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/siddharthgavali11-dev/studentsync.git
   cd studentsync
   ```

2. Open `index.html` in your web browser.

No installation or build step is required.

If your browser blocks location access when the page is opened as a file, serve the folder locally instead and open http://localhost:8000:

```bash
python -m http.server 8000
```

Sign in with one of the demo accounts above, and allow location access when the browser asks to try the geofencing.

## 🔮 Future Enhancements

- Firebase Authentication
- Real-time Database Integration
- Push Notifications
- BLE & Wi-Fi Based Attendance
- QR Code Attendance
- Face Recognition
- Mobile App using Flutter

## 👨‍💻 Author

**Siddharth Gavali**

---

⭐ If you like this project, consider giving it a star on GitHub!
