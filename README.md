# 🚀 Priofy

**Priofy** is a clean, modern, and lightweight task management application built with Flutter. It helps users stay organized by allowing them to create, complete, and delete tasks with all data stored locally using Hive.

Designed with Material 3 and a dark theme, Priofy offers a simple and distraction-free productivity experience.

---

## ✨ Features

- 📝 Add new tasks
- ✅ Mark tasks as completed
- 🗑️ Swipe to delete tasks
- 💾 Offline local storage with Hive
- 🌙 Modern Material 3 dark theme
- 📱 Responsive and clean user interface
- ⚡ Fast and lightweight performance

---

## 📸 Screenshots


| Home | Add Task | Delete Task |
|------|----------|-------------|
| Screenshot | Screenshot | Screenshot |

---

## 🛠 Tech Stack

- Flutter
- Dart
- Hive
- hive_flutter
- flutter_slidable
- Material 3

---

## 📂 Project Structure

```
lib/
├── data/
│   └── database.dart
│
├── pages/
│   └── todo_list.dart
│
├── util/
│   ├── add_task.dart
│   ├── button_use.dart
│   └── todo_tile.dart
│
└── main.dart
```

---

## 📦 Dependencies

```yaml
flutter_slidable
hive
hive_flutter
```

---

## 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/Samirkabirtanjim/priofy.git
```

Navigate to the project

```bash
cd priofy
```

Install dependencies

```bash
flutter pub get
```

Run the application

```bash
flutter run
```

---

## 💾 Local Storage

Priofy uses **Hive**, a lightweight NoSQL database, to save tasks locally. Your tasks remain available even after closing the application.

---

## 🎯 What I Learned

This project helped me improve my understanding of:

- Flutter widget tree
- StatefulWidget lifecycle
- State management using `setState()`
- Local persistence with Hive
- Reusable widget design
- Dialogs and forms
- Swipe actions with `flutter_slidable`
- Material 3 theming

---

## 🔮 Future Improvements

- ✏️ Edit existing tasks
- 🔍 Search tasks
- ⭐ Task priority levels
- 📅 Due dates
- 📂 Categories
- 🎨 Theme switching
- ☁️ Cloud synchronization
- 📊 Task statistics

---

## 👨‍💻 Author

**Samir Kabir Tanjim**

GitHub: https://github.com/Samirkabirtanjim

Learning Flutter by building practical mobile applications.

---

## 📄 License

This project is licensed under the MIT License.
