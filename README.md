# Understanding-Isolates-in-Flutter

A new Flutter project that shows Isolate in Flutter.

## Getting Started

This project is a starting point for a Flutter application.

This Flutter project demonstrates the use of isolates to handle heavy computational tasks without blocking the main thread, ensuring a smooth and responsive user interface.

Key Features
Efficient Data Handling: Fetches and parses a list of 5000 photos using Dart's compute function, which runs in a separate isolate to prevent UI blocking.
Responsive UI: The app remains responsive even when processing large datasets, providing a better user experience.
Modern Flutter Practices: Implements best practices in Flutter for managing asynchronous tasks and optimizing performance.
How It Works
Isolates: The project showcases how to use isolates in Flutter to offload heavy tasks, such as JSON parsing, to a background thread.
compute Function: Utilizes the compute function to parse the fetched photo data in an isolate, keeping the main thread free for UI rendering.
Usage
Clone the repository and run the app using your preferred Flutter development environment. The app will fetch a list of photos from an API, parse the data in an isolate, and display the photos in a responsive UI.

Installation

git clone <repository-url>
cd <project-directory>
flutter pub get
flutter run
Contribution
Feel free to contribute to this project by submitting issues or pull requests. Your feedback and improvements are welcome!

<div style="display: flex; justify-content: center; align-items: center;">
  <div style="text-align: center; margin-right: 20px;">
    <img src="https://github.com/user-attachments/assets/f48a8cfb-f757-4387-bdf9-72250adf9c08" alt="iOS Screenshot" width="300"/>
    <p><strong>iOS</strong></p>
  </div>
  <div style="text-align: center; margin-left: 20px;">
    <img src="https://github.com/user-attachments/assets/86fbdf48-70ac-4638-8fa0-5b5878e92241" alt="iOS Screenshot" width="300"/>
    <p><strong>Android</strong></p>
  </div>
</div>


