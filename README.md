# Android Calculator

A lightweight, functional Android calculator application built with Java and Android Studio. This project demonstrates basic UI/UX principles, event handling, and manual implementation of arithmetic logic and operator precedence.


https://github.com/user-attachments/assets/a5714e46-1d51-4b2e-935c-267afc343673


## 🚀 Features
- **Basic Arithmetic:** Supports addition, subtraction, multiplication, and division.
- **MDAS Logic:** Implements basic order of operations (Multiplication and Division are calculated before Addition and Subtraction).
- **Dynamic UI:** Real-time display updates as buttons are pressed.
- **Edge-to-Edge Design:** Utilizes modern Android layout features for a full-screen experience.

## 🛠️ Technical Implementation
Unlike simple calculators that calculate strictly from left-to-right, this app uses a more sophisticated approach:
- **State Management:** Uses a `Deque<String>` (Double-Ended Queue) to manage numbers and operators.
- **Manual MDAS Handling:** The logic checks for pending multiplication or division operations before adding them to the final calculation queue to ensure mathematical correctness.
- **Precision:** Uses `double` data types to allow for decimal results and large calculations.

## 🏗️ Requirements
- **Android Studio** Jellyfish or newer.
- **Minimum SDK:** API 24 (Android 7.0).
- **Target SDK:** API 34 (Android 14).

## 📥 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/siddhic0311/OIBSIP-CALCULATOR.git
   ```
2. Open the project in **Android Studio**.
3. Build the project and wait for Gradle synchronization.
4. Run the app on an **Emulator** or a physical **Android Device**.

