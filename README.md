# CheckMe - Professional Todo Application

![CheckMe Logo](screenshots/app_icon.png) <!-- Replace with your actual app icon -->

A production-grade todo application built with Flutter, featuring robust state management with Riverpod and adaptive theme switching.

## 📱 Application Preview

<div align="center">
  <img src="screenshots/login_screen.png" width="30%" alt="Login Screen"/>
  <img src="screenshots/home.png" width="30%" alt="Home Screen"/> 
  <img src="screenshots/dark_mode.png" width="30%" alt="Dark Mode"/>
  <img src="screenshots/todo_details.png" width="30%" alt="Details Screen"/>
  <img src="screenshots/add_todo.png" width="30%" alt="Add Todo"/>
  <img src="screenshots/categories.png" width="30%" alt="Categories"/>
</div>

> Screenshots directory: `D:\Desktop\AUCA\MOBILE PROGRAMMING\FlutterApps\screenshots`

## 🚀 Key Features

| Feature                | Implementation Details |
|------------------------|-----------------------|
| **Secure Authentication** | Email validation with regex pattern matching |
| **Todo Management**    | CRUD operations with Riverpod state management |
| **Smart Organization** | Categories (Personal/Work/School/Urgent) with color coding |
| **Time Awareness**     | Due dates with overdue visual indicators |
| **Instant Search**     | Real-time search through todos |
| **Adaptive Theming**   | Light/Dark/System theme modes |

## 📦 Technical Architecture

```mermaid
graph TD
    A[Presentation Layer] --> B[Riverpod Providers]
    B --> C[Business Logic]
    C --> D[Data Models]
    D --> E[Persistence]
```

## ⚙️ System Requirements

- Flutter SDK 3.0+
- Android 8.0+ (API 26) or iOS 13+
- Dart 3.0+

## 📥 Installation Options

### Option 1: Direct APK Download
[![Download APK](https://img.shields.io/badge/Download_APK-v1.0.0-blue?style=for-the-badge&logo=android)](https://github.com/Hugues6221394/Mobile-Programming-Flutter/releases/download/v1.0.0/CheckMe-Todo.apk)

Scan to install:  
![QR Code](https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://github.com/Hugues6221394/Mobile-Programming-Flutter/releases/download/v1.0.0/CheckMe-Todo.apk)

### Option 2: Build from Source
# Clone repository
git clone https://github.com/Hugues6221394/Mobile-Programming-Flutter.git

# Install dependencies
flutter pub get

# Run in debug mode
flutter run

# Build release APK
flutter build apk --release


## 🏗 Project Structure

```
lib/
├── core/
│   ├── constants/      # App constants
│   ├── utils/          # Helper functions
│   └── widgets/        # Reusable components
├── features/
│   ├── auth/           # Authentication flow
│   ├── todos/          # Todo management
│   └── settings/       # Theme and preferences
├── providers/          # State management
└── main.dart           # App entry point
```

## 📚 Documentation

- [State Management Diagram](screenshots/state_management.png)
- [Theme System Documentation](screenshots/theme_system.png)
- [API Reference](#) <!-- Add link if applicable -->

## 🛠 Troubleshooting

| Issue | Solution |
|-------|----------|
| APK won't install | Enable "Install Unknown Sources" in Android settings |
| Build failures | Run `flutter clean` then `flutter pub get` |
| Theme not changing | Verify Riverpod provider scope |

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

## 📬 Contact

For support or feature requests:  
[Create an Issue](https://github.com/Hugues6221394/Mobile-Programming-Flutter/issues)  
Email: [docworld74@gmail.com](mailto:docwrold74@gmail.com)
