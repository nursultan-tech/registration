# untitled8

A new Flutter project.

## Getting Started

# Flutter Project with Firebase Integration

This project demonstrates how to set up a Flutter application with Firebase Authentication and version management through `local.properties`.

## Project Setup

1. **Flutter**: Ensure Flutter is installed. Verify with `flutter doctor`.
2. **Firebase**:
   - Create a new project in Firebase.
   - Add an Android app with the package name `com.example.untitled8`.
   - Download `google-services.json` and place it in `android/app`.
   - Configure Gradle to work with Firebase.
3. **Versioning**: Specify `versionCode` and `versionName` in `local.properties`.

## Running the Project

Run the project using the commands `flutter clean`, `flutter pub get`, and `flutter run`.

## Features

- User registration, login, and password recovery via Firebase Authentication.
- Home screen with a sign-out button.

## Dependencies

Include in `pubspec.yaml`:
- `firebase_core`
- `firebase_auth`
