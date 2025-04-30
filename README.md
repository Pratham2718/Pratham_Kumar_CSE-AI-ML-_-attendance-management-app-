# Pratham_Kumar_CSE-AI-ML-_-attendance-management-app-
An Android app built using Java and Firebase for managing student attendance via QR codes. Features include login via roll number, event listings, reminders, profile view, QR-based entry/exit tracking, and auto-updating attendance to assigned faculty. Designed for college events.


Project Titile: Attendance Management App
Team Members: Aadya Saxena(2301730037)
Ayush Kumar(2301730016)
Pratham Kumar(2301730012)

Short Project Description:
📱 Attendance Management Application (Android, Java + Firebase)
This Android-based Attendance Management Application is a standalone solution developed using Java and Firebase, designed to streamline student event attendance tracking in educational institutions.

✅ Key Features:
🔐 Secure login system using college roll number and custom password (Firebase Authentication).

🗓️ Event dashboard with event details including date, venue, guest info, and registration capability.

⏰ Reminder feature for setting alarms for upcoming events.

🧑‍🎓 Profile section showing student personal details.

📸 QR Code-based attendance system:

Admin-generated time-restricted QR codes for event entry and exit.

Triple-verification system to ensure valid attendance.

📊 Automated attendance logging into Firebase Firestore.

🧑‍🏫 Faculty Notification:

Each student is mapped to a class and faculty.

When a student attends an event, the attendance is automatically sent to the assigned faculty.

🔔 Background reminder scheduling and boot-resilient alarm management.

🛠️ Tech Stack:
Java (Android)

Firebase (Authentication & Firestore)

ZXing (QR Code Scanning)

Android AlarmManager & Broadcast Receivers



📌 Technologies Used:

Java — Core programming language used for Android app development.

XML — For designing UI layouts and custom views.

Firebase Authentication — Handles user sign-in using email (mapped from roll number) and password.

Firebase Firestore — Cloud-based NoSQL database for storing event data, attendance records, and user profiles.

Firebase Realtime Database (optional) — For real-time updates if needed.

Firebase Cloud Messaging (optional) — For future push notifications.

ZXing Library — For scanning and processing QR codes.

Android Studio — IDE used for building and testing the application.


