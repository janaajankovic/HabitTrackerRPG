## Getting Started

Follow these steps to run the project locally.

### Prerequisites

* **Android Studio** installed (latest version recommended).
* A **Firebase account** (free).

### 1. Firebase Setup (Most Important Step)

The app cannot run without Firebase. You need to connect it to your own Firebase project.

1.  Go to the [Firebase Console](https://console.firebase.google.com/).
2.  Create a new project (e.g. "HabitTrackerRPG-Test").
3.  Inside the project, click **"Add app"** and select the **Android** icon.
4.  In the "Android package name" field, enter exactly: **`com.example.habittrackerrpg`**.
5.  Download the **`google-services.json`** file that Firebase provides.
6.  Move that file into your Android Studio project, inside the **`app/`** folder.
7.  In the Firebase Console, open **Build -> Firestore Database** from the left menu.
    * Click "Create database".
    * Select **Start in test mode**. This lets the app write to the database without complex security rules.
8.  In the Firebase Console, go to **Build -> Authentication**.
    * Open the "Sign-in method" tab.
    * Enable **Email/Password** as a sign-in method.

### 2. Running in Android Studio

1.  Open the project in Android Studio.
2.  Wait for Gradle to finish syncing (this can take a few minutes the first time).
3.  Connect a physical Android device (with USB Debugging enabled) or start an emulator.
4.  Select your device from the top menu in Android Studio.
5.  Click the green "Play" icon (▶️ Run 'app').

The app will install and launch on your device or emulator.
