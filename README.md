# Notes Pro - Your Digital Notebook

Welcome to the Notes Pro repository! This Android app allows users to create, manage, and organize their notes using Firebase as the backend. Below, we provide an overview of key files, functionalities, and usage instructions:

## Features

- **User Authentication:** You can safely log in or sign up using Firebase Authentication.
- **Real-time Note Management:** Create, edit, and delete notes. Any changes you make will show up in real-time.
- **Sorting Notes:** Your notes are shown in order of when you created them, from newest to oldest.
- **Logout:** Easily log out with just one click using the menu button.
- **Intuitive UI:** The app has a simple and user-friendly design for managing your notes.

## Files and Activities

- `CreateAccountActivity.java`: Handles user registration with Firebase Authentication.
- `LoginActivity.java`: Manages user login using Firebase Authentication.
- `MainActivity.java`: The app's main screen for viewing and managing notes.
- `Note.java`: Represents the structure of a note.
- `NoteAdapter.java`: RecyclerView adapter for displaying notes in the main activity.
- `NoteDetailsActivity.java`: Allows users to view and edit note details.
- `SplashActivity.java`: Displays a splash screen on app startup.
- `Utility.java`: Contains utility functions for interacting with Firebase.

## Getting Started

1. Clone or download the repository to your local machine.
2. Set up your Firebase project and add the `google-services.json` file.
3. Open the project in Android Studio.
4. Run the app on your Android device or emulator.
5. Register or log in to start managing your notes!

## Usage

- **Add a Note:** Click the "+" button to create a new note.
- **View/Edit a Note:** Tap on a note in the main screen to view or edit its content.
- **Delete a Note:** Swipe left on a note to reveal the delete button.
- **Logout:** Tap the menu button to access the logout option.

## Important Note

- This app uses Firebase for logging in and saving your notes in real-time.
- Make sure your Firebase settings are right for the app to work.
- Always keep your Firebase credentials and API keys safe and secure.

## Resources

- [Firebase Documentation](https://firebase.google.com/docs)
- [Firestore Documentation](https://firebase.google.com/docs/firestore)
- [Firebase UI for Android](https://github.com/firebase/FirebaseUI-Android)
