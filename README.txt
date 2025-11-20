MediAlert - Android Studio Project (Colorful Blue/Green theme)
-------------------------------------------------------------
This project is preconfigured but DOES NOT include google-services.json.
Follow these steps to run:

1) Open this folder in Android Studio (File -> Open -> select the project folder).
2) In Firebase Console:
   - Create a new Android app with package name: com.example.medialert
   - In Authentication -> Sign-in method -> Enable Email/Password
   - Create a Realtime Database
   - Download google-services.json and place it in app/ directory.
3) Build & Run:
   - Sync Gradle (Android Studio will prompt)
   - Run on emulator or device (minSdk 24)

Notes:
- Replace applicationId or package name carefully if you change them in Firebase.
- This project uses AlarmManager for local reminders and Firebase Realtime Database for storage.
