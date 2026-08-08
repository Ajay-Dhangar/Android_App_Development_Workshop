<div align="center">

![Android App Development Workshop Banner](https://github.com/user-attachments/assets/32fb74e6-b763-467e-a74b-8d8e750623f3)

[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)](https://developer.android.com/studio)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

Welcome to the **Android App Development Workshop** repository! This project serves as a comprehensive hands-on guide covering core Android application concepts, architectural fundamentals, and UI components through isolated demonstration apps.

---

## Repository Overview

This repository contains multiple standalone Android Studio projects, each demonstrating a fundamental building block of Android app development:

* **`BroghtCastDemo`**: Implementation of Broadcast Receivers to listen and react to system-wide broadcast announcements (e.g., battery state changes, connectivity updates).
* **`LifeCycleDemo`**: Hands-on demonstration tracking the complete Android Activity Lifecycle methods (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onDestroy`).
* **`MenuDemo`**: Working examples of custom menus in Android, including Options Menu, Context Menu, and Popup Menu UI structures.
* **`MyApplication`**: Baseline starter template demonstrating basic activity orchestration and layout design.
* **`MyCalculator`**: A fully functional calculator application showcasing UI element wiring, event listener binding, and state handling.
* **`MyGFirstProject`**: Initial foundational app structure showcasing basic layout elements and Activity switching.
* **`ServiceDemo`**: Implementation of background operations using Android Services without blocking the main UI thread.
* **`Shivay_01`**: Custom mini-project focusing on component integration and multi-view navigation.

---

## Tech Stack & Prerequisites

* **IDE**: [Android Studio](https://developer.android.com/studio) (Recommended version: Electric Eel or higher)
* **Programming Language**: Java / Kotlin
* **Min SDK**: API Level 21 (Android 5.0 Lollipop) or higher
* **Target SDK**: API Level 33+

---

## Getting Started

Follow these steps to run any of the demo projects locally on your system:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ajay-dhangar/Android_App_Development_Workshop.git
    ```

2. **Open in Android Studio**
* Launch **Android Studio**.
* Click on **Open**.
* Navigate to the cloned folder and select the specific project subfolder you wish to run (e.g., `LifeCycleDemo`).


3. **Build & Sync Gradle**
* Allow Android Studio to download the necessary dependencies and sync the Gradle files.


4. **Run the Project**
* Connect a physical Android device via USB (with **USB Debugging** enabled) or start an Android Virtual Device (AVD) emulator.
* Press `Shift + F10` or click the green **Run** button in Android Studio.

---

## Project Structure

```text
Android_App_Development_Workshop/
├── BroghtCastDemo/        # Broadcast Receiver implementation
├── LifeCycleDemo/         # Activity Lifecycle logging & state management
├── MenuDemo/              # Options, Context, and Popup Menus
├── MyApplication/         # Starter project framework
├── MyCalculator/          # Functional calculation app logic & UI
├── MyGFirstProject/       # Core beginner layout components
├── ServiceDemo/           # Background Service orchestration
└── Shivay_01/             # Multi-screen navigation demo

```

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ajay-dhangar/Android_App_Development_Workshop/issues) if you want to contribute.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/NewDemo`).
3. Commit your changes (`git commit -m 'Add new demo project'`).
4. Push to the branch (`git push origin feature/NewDemo`).
5. Open a Pull Request.

---

## Author

Created with ❤️ by **Ajay Dhangar**

* GitHub: [@Ajay-Dhangar](https://github.com/Ajay-Dhangar)
