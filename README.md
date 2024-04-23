Flutter Chat App with Firebase
This Flutter application is a real-time chat app powered by Firebase. It allows users to register, login, and communicate with each other in real-time.

Features
User Authentication: Users can register and login securely using their email and password.
Real-time Messaging: Chat messages are delivered instantly using Firebase's real-time database.
User Profiles: Users can set up and update their profiles with avatars and status messages.
Online Presence: Users are notified of other users' online status.
Technologies Used
Flutter: A UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
Firebase Authentication: Provides backend services, easy-to-use SDKs, and ready-made UI libraries to authenticate users to your app.
Firebase Realtime Database: A cloud-hosted NoSQL database that lets you store and sync data between your users in real-time.
Firebase Storage: A cloud storage service that allows you to upload and share user-generated content.
Clone the Repository:
git clone <repository-url>
Setup Firebase Project:
Create a new Firebase project on the Firebase console.
Enable Firebase Authentication and Realtime Database.
Download and add the google-services.json file to your Flutter project for Android or GoogleService-Info.plist for iOS.
Configure Firebase:
Update the firebase_core and firebase_auth dependencies in pubspec.yaml.
Initialize Firebase in your Flutter app.
Run the App:
flutter run
