# Dice Roller

A simple Android application that simulates rolling a six-sided die using Jetpack Compose.

## Features

- Roll a virtual six-sided die with a tap of a button
- Display dice faces using vector drawables
- Smooth animations and transitions
- Material Design 3 theming
- Support for both light and dark modes

## Technologies Used

- Kotlin
- Jetpack Compose
- Material Design 3
- Android Vector Drawables
- Gradle Version Catalogs

## Requirements

- Android Studio Arctic Fox or later
- Minimum SDK: 24 (Android 7.0)
- Target SDK: 35
- Kotlin 2.0.0
- Gradle 8.10.2

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/DiceRoller.git
```

2. Open the project in Android Studio

3. Run the app using an emulator or physical device

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/diceroller/
│   │   │   ├── MainActivity.kt       # Main activity and composables
│   │   │   └── ui/theme/            # Theme configuration
│   │   └── res/
│   │       ├── drawable/            # Dice face vector drawables
│   │       └── values/             # Resources (strings, colors, themes)
│   └── test/                      # Unit tests
└── build.gradle.kts              # App-level build configuration
```

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
