# Startup Name Generator Flutter App

This is a simple Flutter application that generates random startup names and allows users to save their favorite ones.

## Features

- **Infinite Scrolling:** Generates new word pairs as the user scrolls.
- **Favoriting:** Allows users to save their favorite word pairs.
- **Navigation:** Separate screen to view saved suggestions.
- **Custom Theme:** Uses the 'Inter' font and a customizable color scheme.
- **Cross-Platform:** Built with Flutter, can be compiled for Android and iOS.

## How to Run

1.  **Ensure Flutter is installed.** If not, follow the instructions on the [Flutter official website](https://flutter.dev/docs/get-started/install).
2.  **Clone or download this project.**
3.  **Create a `fonts` directory** inside the `assets` directory (if `assets` doesn't exist, create it at the root of the project). So the path would be `assets/fonts/`.
4.  **Download the Inter font.** You can get it from [Google Fonts](https://fonts.google.com/specimen/Inter) or other sources. Place `Inter-Regular.ttf` (and any other weights you want to use) into the `assets/fonts/` directory.
    *Make sure the font file name in `pubspec.yaml` matches the actual font file name (e.g., `Inter-Regular.ttf`).*
5.  **Get dependencies:**
    ```bash
    flutter pub get
    ```
6.  **Run the app:**
    ```bash
    flutter run
    ```

## Project Structure

- `lib/main.dart`: Contains the main application code.
- `pubspec.yaml`: Defines project dependencies and assets (like fonts).
- `assets/fonts/`: Directory for font files (you need to create this and add the Inter font).
