<div align="center">
  <h1>🍽️ ShareCare</h1>
  <p><strong>A Food Donation Mobile Application</strong></p>
  <p><em>Reducing food waste, fighting hunger — one donation at a time.</em></p>
</div>

<br>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Features](#features)
- [Screenshots](#screenshots)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## 📖 About The Project

ShareCare is a cross-platform mobile application developed to address **Sustainable Development Goal 2 (SDG 2) — Zero Hunger**. The app tackles the dual problems of food waste and hunger by providing a seamless platform for individuals and businesses to donate surplus food to those in need.

### Problem Statement

In modern society, vast amounts of food are wasted daily from restaurants, stores, and households — contributing to environmental issues and exacerbating food insecurity. At the same time, willing donors lack an efficient way to connect with recipients. ShareCare bridges this gap by offering an intuitive, community-driven solution.

### Objectives

1. Define and implement requirements for a food donation application.
2. Develop a functional mobile app to help those in need access food resources.
3. Test and maximize the app's impact on reducing food waste and aiding underserved communities.

---

## 🛠️ Built With

| Category              | Technology                                                                 | Purpose                                      |
|-----------------------|----------------------------------------------------------------------------|----------------------------------------------|
| **Language**          | [Dart](https://dart.dev/)                                                  | Core programming language                    |
| **Framework**         | [Flutter](https://flutter.dev/)                                            | Cross-platform UI framework                  |
| **Database**          | [SQLite](https://www.sqlite.org/) via [sqflite](https://pub.dev/packages/sqflite) | Local data persistence                       |
| **Charts**            | [Syncfusion Flutter Charts](https://pub.dev/packages/syncfusion_flutter_charts) | Data visualization & analytics               |
| **Image Picking**     | [image_picker](https://pub.dev/packages/image_picker)                      | Select images from gallery or camera         |
| **File Picking**      | [file_picker](https://pub.dev/packages/file_picker)                        | Pick files from device storage               |
| **HTTP Client**       | [http](https://pub.dev/packages/http)                                      | Network requests & API communication         |
| **Image Caching**     | [cached_network_image](https://pub.dev/packages/cached_network_image)      | Efficient image loading & caching            |
| **State Management**  | StatefulWidget / `setState`                                                | Local UI state management                    |
| **Icons**             | [Cupertino Icons](https://pub.dev/packages/cupertino_icons)                | iOS-style icon set                           |

### Supported Platforms

<p align="left">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="iOS"/>
  <img src="https://img.shields.io/badge/Web-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Web"/>
  <img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
</p>

---

## ✨ Features

| Feature                | Description                                                              |
|------------------------|--------------------------------------------------------------------------|
| 🔐 **Authentication**  | User registration and login system for personalized access               |
| 📝 **Donation Form**   | Submit food donations with type, quantity, expiry date, and images       |
| 📜 **Donation History**| Browse a complete log of all past donations                              |
| 🔍 **Donation Details**| View full information for any specific donation record                   |
| 👤 **Profile**         | Manage personal account information and settings                         |
| 📊 **Analytics**       | Visualize donation data with interactive charts                          |
| 📱 **Cross-Platform**  | Runs seamlessly on Android, iOS, Web, macOS, Linux, and Windows          |

---

## 📱 Screenshots

<table>
  <tr>
    <td align="center" width="25%">
      <strong>Splash Screen</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/46a6e9bf-3eb0-4b10-9a5d-baa7fed6a9f7" width="200" alt="Splash Screen"><br>
      <em>App launch screen</em>
    </td>
    <td align="center" width="25%">
      <strong>Login Screen</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/fa9e249a-a66a-4355-89ab-0a64a9a8d4b4" width="200" alt="Login Screen"><br>
      <em>User sign-in</em>
    </td>
    <td align="center" width="25%">
      <strong>Registration</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/aa4f7762-1ac2-4db4-a155-613b14c7c95a" width="200" alt="Registration Screen"><br>
      <em>New user sign-up</em>
    </td>
    <td align="center" width="25%">
      <strong>Home Page</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/ef8e07a9-c51a-48f4-a161-dc35243f0d8a" width="200" alt="Home Page"><br>
      <em>Main navigation hub</em>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <strong>Donation Form</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/3e6e9ab6-9a8a-46a2-8c5f-de9ccf485df6" width="200" alt="Donation Form"><br>
      <em>Submit a food donation</em>
    </td>
    <td align="center" width="25%">
      <strong>Profile</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/46650b15-7983-42ff-a6c0-3f9aec8333bf" width="200" alt="Profile Screen"><br>
      <em>Account management</em>
    </td>
    <td align="center" width="25%">
      <strong>History</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/b3371e31-cca4-49c0-bfb5-8112f42a2d36" width="200" alt="History Screen"><br>
      <em>Past donations log</em>
    </td>
    <td align="center" width="25%">
      <strong>Donation Details</strong><br>
      <img src="https://github.com/Azieyati/ShareCare-MobileApps-using-Dart-and-SQLlite/assets/156404474/d7644213-b62e-4611-b10d-02798307db17" width="200" alt="Details Screen"><br>
      <em>Full donation info</em>
    </td>
  </tr>
</table>

---

## 🏗️ Architecture

ShareCare follows a clean, layered architecture:

```
┌─────────────────────────────────────────────┐
│           Presentation Layer                 │
│         lib/Screens/ (UI Screens)           │
│         StatefulWidget + setState           │
├─────────────────────────────────────────────┤
│              Data Layer                      │
│     lib/sqflite-database/ (SQLite CRUD)     │
├─────────────────────────────────────────────┤
│              Models Layer                    │
│        lib/JsonModels/ (Data Models)        │
└─────────────────────────────────────────────┘
```

- **Presentation Layer** — All UI screens built as `StatefulWidget` components.
- **Data Layer** — SQLite database operations for persistent local storage.
- **Models Layer** — Data models representing users and food donations.

---

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) `>=3.1.3`
- [Dart](https://dart.dev/get-dart) `>=3.1.3`
- Android Studio, Xcode, or VS Code (for platform-specific builds)

### Installation

```bash
# Clone the repository
git clone https://github.com/Azieyati/ShareCareApp.git

# Navigate to the project directory
cd ShareCareApp

# Install dependencies
flutter pub get

# Run the app
flutter run
```

> **Note:** Use `flutter run -d chrome` for web, or specify a device ID with `-d <device-id>`.

---

## 📁 Project Structure

```
lib/
├── main.dart                          # App entry point
│
├── JsonModels/                        # Data models
│   ├── fooddonate.dart                #   Food donation model
│   ├── user_authentication.dart       #   User authentication model
│   └── users.dart                     #   User profile model
│
├── Screens/                           # UI screens
│   ├── splash.dart                    #   Splash / launch screen
│   ├── login.dart                     #   Login screen
│   ├── signup.dart                    #   Registration screen
│   ├── homepage.dart                  #   Home page
│   ├── home_user.dart                 #   User home screen
│   ├── donationformpage.dart          #   Food donation form
│   ├── details_donation.dart          #   Donation details view
│   ├── history_donation.dart          #   Donation history list
│   └── profile.dart                   #   User profile screen
│
└── sqflite-database/                  # Database layer
    └── sqflite.dart                   #   SQLite database helper
```

---

## 📄 License

Copyright &copy; 2024 Azieyati. All rights reserved.

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

---

## 📬 Contact

- **GitHub:** [@Azieyati](https://github.com/Azieyati)
- **Project Link:** [https://github.com/Azieyati/ShareCareApp](https://github.com/Azieyati/ShareCareApp)

---

## 🙏 Acknowledgments

- [Flutter](https://flutter.dev/) — Cross-platform UI framework
- [Syncfusion](https://www.syncfusion.com/flutter-widgets/charts) — Charts & data visualization
- [Cupertino Icons](https://pub.dev/packages/cupertino_icons) — iOS-style icon set
- [SDG 2: Zero Hunger](https://sdgs.un.org/goals/goal2) — United Nations Sustainable Development Goal

---

<div align="center">
  <p>
    Made with ❤️ to help achieve <strong>Zero Hunger</strong>
  </p>
  <p>
    <sub>Azieyati &copy; 2024. All rights reserved.</sub>
  </p>
</div>
