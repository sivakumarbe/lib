🩺 SwastAid – Smart Health Assistant

SwastAid is a Flutter-based mobile healthcare assistant designed to help diabetic patients manage daily medication routines and understand blood sugar reports using OCR technology. get meal suggestion based on the glucose values to recover fast.

The application focuses on simplicity, offline storage, and accessibility, especially for elderly users.

🚀 Key Features

📸 OCR-Based Blood Report Analysis
Automatically extracts glucose values from uploaded blood reports using Google ML Kit.

🩸Glucose Detection
Supports detection of:

Post-meal (Post-prandial) glucose

Best glucose value categorization (Normal / Mild / Moderate / High)

💊 Pill Reminder System

Scheduled medication reminders

Local notifications with time-based scheduling

Test mode for rapid reminder verification

🍽️ Personalized Meal Suggestions
Dynamically adjusts meal suggestions based on the latest glucose values.

📋 Activity Menu Dashboard
A user-friendly Activity Menu for navigating:

Upload Reports

View OCR Results

Get Meal Suggestions

Pill Reminders

Activity

🗂️ Local Data Storage

Glucose values and user preferences stored locally

No cloud dependency

Privacy-first approach

🧠 Problem Statement

Many diabetic patients face difficulty:

Understanding blood test reports

Maintaining consistent medication routines

Managing diet based on health data

SwastAid solves these problems by combining OCR, automated reminders, and personalized meal logic into a single easy-to-use mobile application.

🛠️ Tech Stack

Framework: Flutter (Dart)

State Management: Provider

OCR: Google ML Kit – Text Recognition

Notifications: Flutter Local Notifications

Data Storage: SharedPreferences & Local File Storage

Platform: Android

Architecture: Provider-based modular design

📂 Project Structure (Source Code Overview)
lib/
C:.
│   main.dart
│   
├───core
│   ├───constants
│   ├───theme
│   │       app_theme.dart
│   │       colors.dart
│   │       text_styles.dart
│   │
│   └───utils
│           sugar_level_detector.dart
│
├───models
│       meal_plan_model.dart
│
├───provider
│       meal_provider.dart
│       report_provider.dart
│       settings_provider.dart
│
├───routes
│       app_routes.dart
│
├───screens
│   ├───activity
│   │       activity_screen.dart
│   │
│   ├───home
│   │       home_screen.dart
│   │
│   ├───meals
│   │       meal_day_view_screen.dart
│   │       meal_suggestion_screen.dart
│   │
│   ├───reminders
│   │       pill_reminder_screen.dart
│   │
│   ├───reports
│   │       ocr_result_screen.dart
│   │       upload_report_screen.dart
│   │
│   ├───settings
│   └───sos
├───services
│   │   meal_service.dart
│   │   ocr_service.dart
│   │   tts_service.dart
│   │
│   └───notifications
│           notification_service.dart
│           schedule_manager.dart
│
└───widgets
        tile_card.dart

🔐 Privacy & Data Safety

All health data is stored locally on the device

No user login required

No data is uploaded to any server

No third-party data sharing

This design ensures privacy compliance and Play-Store safety.

🔮 Future Enhancements

Notification for diet menu & Activities 

Reminder for Hospital visit

Automatically book appointments

Accessibility improvements


👨‍💻 Developer

Sivakumar A
Aspiring AI|ML Engineer.
Interested in providing AI driven solution for Real world problems.

📌 Notes for Recruiters

This is a real-world healthcare project, not a tutorial app

Demonstrates applied OCR, state management, notifications, and UI design

Designed with privacy, elderly usability, and offline-first principles.
