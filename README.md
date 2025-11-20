# MediAlert
An Android medicine reminder app built using Kotlin and Firebase. Includes login, profile, add medicine, and history tracking modules.
📱 MediAlert – Medicine Reminder Android Application

MediAlert is an Android application designed to help users manage their daily medicines with timely reminders, dosage tracking, and history monitoring.
This app ensures that users never miss their medication schedule and can maintain their health effectively.

🚀 Key Features

User Authentication using Firebase (Login & Registration)

Add Medicine with name, dosage, total tablets, and daily timings

Automatic Notifications & Alerts for every medicine

Medicine History Tracking (taken / missed)

Profile Management

Firebase Realtime Database for storing user data

Clean & Modern UI built using Material Design

🛠️ Technology Stack
Component	Technology Used
Frontend	Android XML, Material UI
Backend	Kotlin
Database	Firebase Realtime Database
Authentication	Firebase Auth
Notification Engine	AlarmManager & NotificationManager
Build System	Gradle
📂 Project Structure
MediAlert/
│── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/medialert/
│   │   │   │   ├── activities/       → Login, Register, Dashboard, Add Medicine
│   │   │   │   ├── model/            → Medicine.kt, User.kt
│   │   │   │   ├── adapter/          → HistoryAdapter, MedicineAdapter
│   │   │   │   ├── utils/            → AlarmHelper.kt, FirebaseUtils.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/           → XML files for screens
│   │   │   │   ├── values/           → colors.xml, strings.xml, styles.xml
│   ├── AndroidManifest.xml
│── build.gradle (Module)
│── build.gradle (Project)
│── google-services.json

🔔 How the Alarm System Works

User adds a medicine with timings

AlarmManager schedules exact alarm times

When time triggers → Notification shows medicine details

User marks as Taken or Missed

History updates in Firebase

🧪 Screens Included

Login / Register

Dashboard

Add Medicine

View Medicines

Medicine History

Profile Page

📥 Installation (For Users)

Clone or download the project

Open in Android Studio

Run on emulator or physical device (API 28+)

Add your own google-services.json if needed

🧑‍💻 Contribution

Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Submit a Pull Request

📞 Contact

If you have any doubts or issues:

Developer: Steve Deepak
Email: (Add your email here)

⭐ Support

If this project helped you, please consider giving it a ⭐ on GitHub!
