# 🧠 Face Recognition-Based Attendance Tracking System

A Python-based project that uses **Face Recognition** to automate attendance marking in classrooms or workplaces. It captures faces in real-time, matches them against stored data, and logs attendance efficiently and accurately without duplicate entries.

---

## 🎯 Objective

The primary goal of this project is to eliminate manual attendance systems using **Computer Vision** and **Facial Recognition** technologies. It ensures high accuracy and can be deployed in real-time environments like schools, offices, and events.

---

## 🔍 Features

- 🎥 Real-time face detection via webcam
- 🧑‍🎓 Automatic face recognition using stored images
- 📅 Attendance logging with date & time
- 💾 CSV file generation for attendance reports
- 🔄 Duplicate entry prevention
- 📸 Easy registration of new faces

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**:
  - `face_recognition`
  - `OpenCV`
  - `NumPy`
  - `datetime`
  - `os`, `csv`

---

## 📁 Folder Structure

├── app.py # Entry point for Flask server
├── templates/ # HTML templates for pages
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ ├── attendance.html
│ └── dashboard.html
├── static/ # CSS, JS, and static files
│ ├── login.css
│ ├── register.css
│ ├── dashboard.css
│ ├── attendance.css
│ └── index.js
├── images/ # Stored face images
│ ├── Girish.jpg
│ └── Abhiram.jpg ...
├── instance/ # SQLite database
│ └── attendance.db
├── logs/ # Logging folder
│ └── app.log
├── screenshots/ # UI screenshots
│ └── Screenshot_*.png
├── face_detection.py # Real-time face detection
├── encode_faces.py # Encode face images
├── attendance.py # Attendance logic
├── capture_face.py # Capture and save new faces
├── models.py # Database model (if using SQLAlchemy)
├── web.py # Optional routes/scripts
├── requirements.txt # Dependencies
└── README.md


---

## ⚙️ Features

- ✅ Real-time face detection and recognition
- ✅ Web-based login/register system
- ✅ Attendance marking with time and date
- ✅ SQLite database integration
- ✅ Encoded face caching for faster processing
- ✅ Logs and screenshots stored for auditing
- ✅ Responsive front-end (HTML/CSS)

---

## 💻 Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Face Recognition**: `face_recognition`, `OpenCV`
- **Database**: SQLite (via Flask or SQLAlchemy)

---

## 🚀 Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/girishnalkar/Face-Recognition-based-attendence-tracking-system-using-python.git
cd Face-Recognition-based-attendence-tracking-system-using-python
```

### 2. Install dependencies:
```bash
pip install -r requirements.txt
```

### 3. Encode faces:
```bash
python encode_faces.py
```

### 4. Run the app:
```bash
python app.py
```
Open browser at http://127.0.0.1:5000

📝 **Attendance Format (CSV or DB)**
Each entry contains:
  pgsql
  Name | Date | Time
    Sample:
    Girish Nalkar | 2025-07-28 | 09:12:03

📸 **Screenshots**
![Login Page](screenshots/Screenshot%202025-07-28%20095939.png)
![Dashboard](screenshots/Screenshot%202025-07-28%20095946.png)

🔐 **Notes**
All user images are stored under /images/
Database file is stored at /instance/attendance.db
Logs are maintained in /logs/app.log

📦 **Future Improvements**
 -Flask admin dashboard for admin users
 -Email notification system
 -Cloud storage integration
 -REST API for mobile clients

 🙋‍♂️ **Author**
Name: Girish Nalkar
GitHub: @girishnalkar

📜 **License**
This project is for educational and academic purposes only.
