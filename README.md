Course Dashboard App (Flutter)

Course Dashboard is a modern Flutter application designed to help users browse, enroll in, and track progress in various courses. Whether you're a student, instructor, or life-long learner, this app makes it easy to stay organized and on track with your learning goals.

✨ Features

📚 List of available courses

🧑‍🏫 Course detail pages with lessons/modules

📈 Track progress in each course

🔖 Bookmark/favorite courses

🔍 Search and filter courses

📝 Enroll/unenroll functionality

🌓 Light/Dark mode support

🔗 (Optional) Integration with backend (Firebase/API)

🛠️ Built With

Flutter (Dart)

State Management: Provider / Riverpod / Bloc / GetX

Local Storage: Hive / SharedPreferences / SQLite

Backend: Firebase / Supabase / Custom REST API (optional)

📱 Screenshots

Add screenshots or gifs here if available (e.g., home screen, course detail page, progress tracker)

🚀 Getting Started
Prerequisites

Flutter SDK: Install here

Android Studio / VS Code

Emulator or real device

Installation

Clone the repository

git clone https://github.com/your-username/course-dashboard-app.git
cd course-dashboard-app


Install dependencies

flutter pub get


Run the app

flutter run

📁 Project Structure
lib/
├── main.dart
├── models/
│   └── course.dart
├── screens/
│   ├── home_screen.dart
│   ├── course_detail_screen.dart
│   └── progress_screen.dart
├── widgets/
│   ├── course_card.dart
│   └── progress_bar.dart
├── services/
│   └── course_service.dart
├── providers/
│   └── course_provider.dart
└── utils/
    └── constants.dart

📘 Sample Course Model
class Course {
  final String id;
  final String title;
  final String description;
  final String instructor;
  final int totalLessons;
  final int completedLessons;
  final String thumbnailUrl;

  Course({
    required this.id,
    required this.title,
    required this.description,
    required this.instructor,
    required this.totalLessons,
    required this.completedLessons,
    required this.thumbnailUrl,
  });
}

✅ Future Improvements

✅ User authentication

✅ Online video integration (YouTube, Vimeo, etc.)

✅ Backend support with real-time updates

✅ PDF and media support in lessons

✅ Notifications/reminders

✅ Certification generation after course completion

🤝 Contributing

Open to community contributions! Please fork the repo and submit a pull request.
