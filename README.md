# currency_rate_calculator

A Flutter-based currency converter application with Firebase authentication, live API integration.

## Setup Steps

1. Flutter & Dart Versions

     Flutter: 3.27.1

     Dart: 3.6.0

     flutter --version

2. Firebase Configuration

     Create a Firebase project at Firebase Console.
   
     Enable Authentication → Email/Password.

     Download the google-services.json

     Add Firebase dependencies in pubspec.yaml:
           firebase_core: ^2.25.0
           firebase_auth: ^4.6.0

     Initialize Firebase in main.dart

3. How to Run

      flutter run
