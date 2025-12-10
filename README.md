# Hello Moringa – Flutter Beginner App  
A simple Flutter mobile application created as part of the **Moringa School AI Capstone Project: Prompt-Powered Kickstart – Building a Beginner’s Toolkit for Flutter**.

This project demonstrates how to set up Flutter, create a basic UI, and run the app using VS Code and Git Bash.

---

## Project Overview  
This is a minimal Flutter app that displays:

```
Hello Moringa!
```

centered on the screen.  
It serves as a beginner-friendly guide for anyone starting their Flutter journey using AI-assisted learning.

---

##  Objective  
- Learn the basics of Flutter through AI-assisted exploration  
- Build and run a simple Flutter app  
- Document the steps clearly so another beginner can replicate them  
- Push and maintain code in GitHub using VS Code + Git Bash  

---

##  Technologies Used  
- **Flutter** (UI Framework)  
- **Dart** (Programming Language)  
- **Android Studio** (for emulator)  
- **VS Code** (for coding)  
- **Git + Git Bash** (for version control)  
- **GitHub** (code hosting)  

---

##  Project Structure  
```
hello_moringa/
│
├── lib/
│   └── main.dart
│
├── android/
├── ios/
├── web/
├── test/
│
├── pubspec.yaml
└── README.md
```

---

##  Installation & Setup Instructions  

### **1. Install Flutter**
Download Flutter:  
https://docs.flutter.dev/get-started/install

Extract and add Flutter to PATH, then verify installation:

```bash
flutter doctor
```

Install missing components if any.

---

### **2. Create the Project**
``` Git bash
flutter create hello_moringa
cd hello_moringa
```

---

### **3. Open Project in VS Code**
```bash
code .
```

---

### **4. Run the App**
Start emulator (Android Studio) **or** connect a phone.

Then run:

```bash
flutter run
```

---

##  Minimal Working Example (main.dart)

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home: Scaffold(
      body: Center(
        child: Text(
          'Hello Moringa!',
          style: TextStyle(fontSize: 24),
        ),
      ),
    ),
  ));
}
```

###  Expected Output  
A centered text saying **Hello Moringa!** on a white screen.

---

## AI Prompt Journal  
Prompts used during the project:

### **Prompt 1:**  
*“Explain Flutter widgets for a beginner.”*  
- Helped me understand Flutter’s UI structure.

### **Prompt 2:**  
*“How do I install Flutter on Windows?”*  
- Guided me through installation and PATH setup.

### **Prompt 3:**  
*“Generate a simple Flutter UI example.”*  
- Provided the basis of the `main.dart` example.

### **Prompt 4:**  
*“Fix this error: Flutter SDK not found.”*  
- Helped resolve PATH issues.

---

##  Common Issues & Fixes  

### ❌ **Flutter SDK not found**
✔ Fix: Add `bin` directory to PATH

### ❌ **Emulator not launching**
✔ Fix: Install Android Virtual Device (AVD) in Android Studio

### ❌ **Gradle build error**
✔ Fix: Update Android dependencies or run:

```bash
flutter clean
flutter pub get
```

---

##  References  
- Flutter Documentation: https://docs.flutter.dev  
- Widget Catalog: https://docs.flutter.dev/ui/widgets  
- Dart Basics: https://dart.dev/guides  
- YouTube Flutter Tutorials  

---

##  How to Push This Project to GitHub  

1. Initialize git:  
```bash
git init
```

2. Add files:  
```bash
git add .
```

3. Commit:  
```bash
git commit -m "Initial Flutter app"
```

4. Add GitHub repo:  
```bash
git remote add origin https://github.com/Tashysam/flutter_api.git
```

5. Push:  
```bash
git branch -M main
git push -u origin main
```

---

## 🎉 Final Notes  
This project is designed to help beginners learn Flutter quickly
