# To-Do List Application

This is a simple To-Do List application built using Dart and Flutter. The app allows users to add, delete, and mark tasks as completed.

## Features

- Add new tasks
- Delete existing tasks
- Mark tasks as completed
- Save tasks using Hive (local storage)

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/) with Flutter and Dart plugins

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/davitm7/ToDoList.git
    ```
2. Navigate to the project directory:
    ```sh
    cd ToDoList
    ```
3. Install dependencies:
    ```sh
    flutter pub get
    ```

### Running the App

1. Connect your mobile device or start an emulator.
2. Run the app:
    ```sh
    flutter run
    ```

## Building the APK

To build the APK, run:
```sh
flutter build apk
```
The generated APK can be found in the `build/app/outputs/flutter-apk/` directory.

### Download the APK

You can download the APK from the following link:
[Download APK](https://drive.google.com/file/d/1nP3M3tbm4im6MJQ555P3M21pzb0DwhJU/view?usp=sharing)

## Usage

1. On the main screen, you can see the list of tasks.
2. To add a new task, click on the floating action button (`+`) and enter the task details.
3. To mark a task as completed, click on the checkbox next to the task.
4. To delete a task, swipe the task to the left and click on the delete icon.

## Folder Structure

```
.
├── android                 # Android-specific files
├── ios                     # iOS-specific files
├── lib
│   ├── data
│   │   └── database.dart   # Database handling using Hive
│   ├── pages
│   │   └── homepage.dart   # Main screen of the application
│   ├── util
│   │   ├── dialog_box.dart # Custom dialog box for adding tasks
│   │   └── todo_tile.dart  # Custom widget for displaying tasks
│   └── main.dart           # Entry point of the application
├── test                    # Unit tests
├── pubspec.yaml            # Project dependencies and metadata
└── README.md               # Project documentation
```

## Dependencies

- `flutter_slidable`: For swipeable list items
- `hive`: For local storage
- `hive_flutter`: For integrating Hive with Flutter
- `fluttertoast`: For displaying toast messages

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Flutter](https://flutter.dev/)
- [Hive](https://pub.dev/packages/hive)
- [flutter_slidable](https://pub.dev/packages/flutter_slidable)
- [fluttertoast](https://pub.dev/packages/fluttertoast)

---

Developed by [Davit Mamuladze](https://github.com/davitm7)
