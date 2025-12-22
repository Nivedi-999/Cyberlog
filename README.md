# Cyberlog

# Session 1

Cyberlog is a Flutter-based mobile application created to understand the foundations of cross-platform development. 
This project helped me explore the differences between native and cross-platform development, the role of hot reload in 
improving development speed, and the widget-based structure that forms the core of Flutter applications.

Native vs Cross-Platform Development
Native apps use platform-specific languages and toolchains (Kotlin/Android Studio and Swift/Xcode).
Cross-platform frameworks such as Flutter allow deployment to multiple platforms using a single codebase.

Hot Reload
Enables instant reflection of UI and logic changes without restarting the entire application.
Improves development efficiency and iteration speed.

Widgets
Every UI element in Flutter is a widget.
Understood the basics of StatelessWidget, MaterialApp, Scaffold, AppBar, and Text widgets.

Setup and Installation
1. Install Flutter
Download the Flutter SDK and extract it to a simple directory (e.g., C:\flutter).
Add its bin folder to the system PATH.

2. Verify Installation
Run: flutter doctor
Resolve all errors before proceeding.

3. Create the Project
flutter create cyberlog

4. Run the Application
cd cyberlog
flutter run

<img width="166" height="337" alt="running_emulator_for_portfoli1" src="https://github.com/user-attachments/assets/8116c95b-ced3-487b-b1e8-e2d04ee14787" />

# Session 2

Just-In-Time (JIT) Compilation
Used during development to compile Dart code while the app is running.
Enables Flutter’s Hot Reload by quickly injecting updated code into the active app.
Supports rapid UI experimentation, debugging, and fast iteration cycles.
Prioritizes developer speed and flexibility over execution performance.

Ahead-Of-Time (AOT) Compilation
Used for generating release builds before publishing to the Play Store or App Store.
Converts Dart code into optimized native machine code ahead of execution.
Provides faster startup time, smoother animations, and better runtime performance.
Prioritizes user experience, efficiency, and production-grade speed.

Using Dart Conditionals (Even/Odd Logic)
To determine whether a number is even or odd, Dart’s if-else conditional structure was used. 
The logic checks whether the number is divisible by 2 using the modulo operator (%). If number % 2 == 0, the number is classified as even; otherwise, it is odd.
This exercise reinforced several core concepts:
How decision-making works in Dart using if, else if, and else statements
How comparison and logical operators (==, !=, %) are applied
How application logic directly influences the displayed UI
The Even/Odd Checker app also demonstrated how user input can be processed and evaluated dynamically, which is essential in real-world Flutter apps that react to user-driven events.

String Interpolation
Dart’s string interpolation feature was used to create the final result message in a clear and readable format. 
Instead of manually concatenating strings, interpolation allows the embedding of variables or expressions directly inside a string using: $variable for simple values
${expression} for complex calculations or logic

Example:
"The number $number is ${resultText}."
Using string interpolation ensures cleaner syntax, fewer formatting errors, and more readable UI text. 
It is especially useful in Flutter, where dynamic text updates are common in interactive screens and forms.

<img width="202" height="432" alt="portfolio_2" src="https://github.com/user-attachments/assets/95bfca9b-651d-49c3-b01a-123cdb68b918" />

# Session 3
#CyberLog - Flutter Activity Logger

#1. Custom Class: `Log`
- Created a structured `Log` class with:
  - `action` (String)
  - `timestamp` (DateTime)
  - `status` (String)

#2. Data Modeling with List<Log>
- Instantiated a `List<Log>` containing 4 realistic sample security events.
- Used real `DateTime` objects for accurate logging.

#3. Efficient UI Rendering with List.map()
- Used the powerful `.map()` method on the logs list to **dynamically generate** a `Card` + `ListTile` for each log entry.
- This is the **Flutter's recommended way to render lists** — clean, efficient, and scalable.

#Benefits Shown
- **Classes** give structure to data (like database records)
- **List iteration with map()** avoids repetitive code and makes adding new logs automatic
- Clean separation of data and UI

Perfect example of Object-Oriented Programming + Functional Reactive UI in Flutter.

<img width="167" height="337" alt="portfolio_3" src="https://github.com/user-attachments/assets/02395537-d54c-4c6b-b7dc-cd93c7ed6079" />

# Session 4
<img width="179" height="365" alt="image" src="https://github.com/user-attachments/assets/2e96e75d-c1e0-44ef-a8d0-d5eefc396fbe" />

# Session 5
<img width="193" height="411" alt="portfolio_5" src="https://github.com/user-attachments/assets/538af14d-8763-4005-ad3f-d5a5e1fef6c9" />

# Session 6
<img width="187" height="341" alt="portfolio_6(1)" src="https://github.com/user-attachments/assets/a4bada39-8aa8-4cf9-845c-c894d8c3610d" />

<img width="179" height="342" alt="portfolio_6(2)" src="https://github.com/user-attachments/assets/f1f5d6a2-4077-4ba4-82e2-c4df0b1d70e1" />

<img width="184" height="340" alt="portfolio_6(3)" src="https://github.com/user-attachments/assets/3b5bf533-f78a-4bf9-86e8-7e69e43b2a63" />

# Session 7
<img width="297" height="639" alt="image" src="https://github.com/user-attachments/assets/d41f5002-9324-4245-9b31-47cb32ad33f4" />

<img width="310" height="637" alt="image" src="https://github.com/user-attachments/assets/b16eeae0-62f4-4da2-b1ca-b9a659384a55" />

<img width="294" height="631" alt="image" src="https://github.com/user-attachments/assets/f84c20d4-4f02-436f-aa42-4b443be5e0de" />

# Session 8
<img width="185" height="396" alt="portfolio_8" src="https://github.com/user-attachments/assets/2bd14146-eb23-49b7-b4c2-5fbbcac6ac69" />

# Session 9
<img width="179" height="365" alt="portfolio_9" src="https://github.com/user-attachments/assets/8ef24bd2-3460-4615-83a1-7812cee012d0" />
