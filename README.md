Notes Pro - Your Digital Notebook
Welcome to the Notes Pro repository! This Android app helps you create, organize, and manage your notes. It uses Firebase as the backend. Below, we'll give you an overview of important files, what the app can do, and how to use it:

Features
User Authentication: You can safely log in or sign up using Firebase Authentication.
Real-time Note Management: Create, edit, and delete notes. Any changes you make will show up in real-time.
Sorting Notes: Your notes are shown in order of when you created them, from newest to oldest.
Logout: Easily log out with just one click using the menu button.
Easy to Use: The app has a simple and user-friendly design for managing your notes.
Files and Activities
CreateAccountActivity.java: This file manages user registration.
LoginActivity.java: Handles user login.
MainActivity.java: This is the main screen of the app where you can see and manage your notes.
Note.java: Defines how a note looks.
NoteAdapter.java: This helps show your notes in the main screen.
NoteDetailsActivity.java: Lets you see and edit the details of a note.
SplashActivity.java: Shows a welcome screen when you start the app.
Utility.java: Contains helpful functions for working with Firebase.
Getting Started
First, download or clone the repository to your computer.
Set up a Firebase project and add the google-services.json file to the project.
Open the project in Android Studio.
Run the app on your Android device or an emulator.
Sign up or log in to start using the app and managing your notes!
Usage
Add a Note: Tap the "+" button to make a new note.
View/Edit a Note: Just tap on a note in the main screen to see or change it.
Delete a Note: Swipe left on a note to delete it.
Logout: Tap the menu button to log out.
Important Note
This app uses Firebase for logging in and saving your notes in real-time.
Make sure your Firebase settings are right for the app to work.
Always keep your Firebase credentials and API keys safe and secure.
Resources
Firebase Documentation
Firestore Documentation
Firebase UI for Android
