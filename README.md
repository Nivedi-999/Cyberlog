#Cyberlog

#Session 1
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

#Session 2
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
