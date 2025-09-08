# Health Style App

An Android mobile application that integrates sensor data capture and Google Drive backup.  
This project demonstrates the use of real-time sensor monitoring on Android devices, user interface interaction via Android activities/fragments, and data persistence through cloud synchronization.


## 🚀 Features

- 📱 **Sensor Integration**: Collects real-time data from the device's built-in sensors (e.g., accelerometer, gyroscope).  
- ☁️ **Google Drive Backup**: Supports uploading and storing sensor data files to a connected Google Drive account.  
- 💾 **Local Storage**: Saves sensor logs to local storage in structured formats (e.g., CSV or JSON).  
- 🧪 **Instrumented UI Tests**: Includes UI-level test cases using the Espresso framework.  
- 🖼️ **User-Friendly Interface**: Simple and clean UI for starting/stopping recording, uploading data, and viewing logs.


## 🛠️ Tech Stack

- **Platform**: Android (SDK 30+)  
- **Language**: Java  
- **UI Components**: Activities, Fragments, RecyclerView  
- **APIs**: Android Sensor API, Google Drive REST API  
- **Build System**: Gradle  
- **Testing**: Espresso for instrumented UI tests


## ⚙️ Installation & Setup

To run the app locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jingwenzz/AndroidApp.git
   
2. Open the project in **Android Studio** (Electric Eel or newer).

3. Connect a physical device or start an Android Emulator.

4. Build and run the app:
   ```bash
   ./gradlew installDebug

5. Google Drive API setup (optional)
  Ensure that you’ve configured Google Drive API access if testing upload functionality.

## 📂 Repository Structure
  ```bash
  AndroidApp/
  │── app/ # Android Studio app modules (source code)
  │ ├── src/
  │ │ ├── main/
  │ │ │ ├── java/ # Java source code
  │ │ │ └── res/ # Layouts, drawables, strings, etc.
  │ │ └── androidTest/ # Instrumented tests (Espresso framework)
  │ └── build.gradle # Gradle build file for the app module
  │
  ├── .gitignore # Files/directories to ignore in Git
  ├── LICENSE # Project license (MIT)
  ├── README.md # Project documentation
  └── build.gradle / settings.gradle # Project-level Gradle configs
  ```
