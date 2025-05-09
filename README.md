# TickList 📝

**TickList** is a lightweight, modern To-Do Android app that helps you stay organized and productive. It features a clean UI, homescreen widget, and a persistent notification so you never miss a task.

## ✨ Features

- ✅ Add, edit, and delete to-do tasks with ease
- 📋 Realtime updates using Room + LiveData
- 🧱 Homescreen widget with live task list
- 🔔 Persistent notification with quick access
- 💾 All data is stored locally on device
- 🎨 Material Design UI with dark/light support

## 📱 Screenshots

*(Add your screenshots here)*

## 📦 Tech Stack

- **Language**: Kotlin
- **UI**: Material Components, RecyclerView, ConstraintLayout
- **Architecture**: MVVM (ViewModel, LiveData, Repository)
- **Persistence**: Room (SQLite wrapper)
- **Widgets**: AppWidgetProvider + RemoteViews
- **Notification**: Foreground Service with ongoing notification

## 📂 Project Structure

```
TickList/
├── app/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/example/ticklist/
│ │ │ │ ├── data/ # Room DB, DAO, Entities
│ │ │ │ ├── ui/ # Activities, ViewModels, Adapters
│ │ │ │ ├── widget/ # AppWidgetProvider, Service
│ │ │ │ ├── service/ # ForegroundService for persistent notification
│ │ │ │ └── utils/ # Extensions, constants
│ │ │ ├── res/
│ │ │ │ ├── layout/ # XML UI layouts
│ │ │ │ ├── xml/ # Widget metadata
│ │ │ │ └── values/ # Strings, themes

```


## 🚀 Getting Started

### Prerequisites

- Android Studio Giraffe or later
- Kotlin 1.8+
- Minimum SDK: 21 (Lollipop)
- Target SDK: 33+

### Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/TickList.git
   cd TickList
2. Open in Android Studio.

3. Build and run on emulator or real device.

4. Grant notification permission (for Android 13+).

## 🧪 Testing
- Add tasks from the main screen.

- Check if tasks reflect in:

-- ✅ The homescreen widget

-- 🔔 The persistent notification

- Try marking tasks done, editing, and deleting.

## 📌 TODO
- Add task reminders with alarms

- Sync with cloud using Firebase

- Add animations and themes

- Import/export task list

## 🛡️ License
MIT License. See LICENSE for details.

## 🙌 Acknowledgements
- Android Jetpack

- Material Components

- Room Persistence Library

- Glance Widgets (if using Jetpack Glance)

Made with ❤️ by Anshuman