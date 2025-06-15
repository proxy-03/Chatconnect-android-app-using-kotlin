# Chatconnect - Real-Time Chat App

Chatoon is a modern Android group chat application built with Jetpack Compose and Firebase. It allows users to register, log in, create chat rooms, and exchange messages in real time. The app features a clean UI, dynamic theming, and robust authentication.

## Getting Started

### Prerequisites

- Android Studio (Flamingo or newer recommended)
- Android device or emulator (API 28+)
- [Firebase Project](https://console.firebase.google.com/) with Authentication and Firestore enabled

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/android-chatconnect-real-time-chat-app.git
   cd android-chatconnect-real-time-chat-app
   ```

2. **Firebase Configuration:**
   - Create a Firebase project.
   - Enable Email/Password Authentication.
   - Create a Firestore database in test mode.
   - Download the `google-services.json` file and place it in `app/`.

3. **Build the project:**
   - Open the project in Android Studio.
   - Let Gradle sync and download dependencies.

4. **Run the app:**
   - Connect your device or start an emulator.
   - Click **Run** in Android Studio.

## Project Structure

```
app/
 ├── src/
 │    ├── main/
 │    │    ├── java/com/example/myapplication/
 │    │    │    ├── view/           # UI screens (login, register, home, chatroom)
 │    │    │    ├── nav/            # Navigation logic
 │    │    │    ├── ui/theme/       # App theming (colors, typography)
 │    │    │    └── Constants.kt    # App-wide constants
 │    │    ├── res/                 # Resources (layouts, drawables, values)
 │    │    └── AndroidManifest.xml
 │    └── ...
 ├── build.gradle
 └── google-services.json
```
