📱 Simple Calculator App (Android - Java)

This is a basic calculator app built in Java using Android Studio.
It allows users to perform simple arithmetic operations: Addition, Subtraction, Multiplication, and Division.

🚀 Features

Enter two numbers and perform calculations

Supports +, -, ×, ÷ operations

Handles division by zero gracefully

Minimal UI, easy to understand

📂 Project Structure
CalculatorApp/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/calculatorapp/MainActivity.java
│   │   │   ├── res/layout/activity_main.xml
│   │   │   ├── AndroidManifest.xml
│   │   │   └── res/values/ (colors, strings, themes)
│   └── build.gradle
│
└── README.md

🛠️ Installation & Setup

Open Android Studio

Create a new Empty Activity Project

Copy the following files into your project:

MainActivity.java

activity_main.xml

AndroidManifest.xml (make sure android:exported="true" is added for Android 12+)

Sync Gradle & Run on an Emulator / Android Device

📜 Code Snippets

MainActivity.java

btnAdd.setOnClickListener(v -> calculate('+'));
btnSub.setOnClickListener(v -> calculate('-'));
btnMul.setOnClickListener(v -> calculate('*'));
btnDiv.setOnClickListener(v -> calculate('/'));

📷 Screenshots (Optional)

(You can add emulator/device screenshots here)

⚡ Requirements

Android Studio Arctic Fox or newer

Java 8+

Min SDK: 21 (Android 5.0 Lollipop)

Target SDK: 33+ (Android 13)

📄 License

This project is free to use for learning purposes.
