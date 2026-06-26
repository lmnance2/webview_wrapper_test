# Android WebView Wrapper

> A simple Android application that wraps a locally hosted web application inside a native Android app using WebView and Jetpack Compose.

> **Project Status:** Prototype

This project demonstrates how to embed a web application in a native Android app using `WebView`. It is intended as a starting point for testing responsive web applications on Android devices before implementing fully native functionality.

---

# Features

- Native Android application built with Kotlin
- Jetpack Compose UI
- Embedded `WebView`
- JavaScript support enabled
- Loads a locally hosted development server

---

# Technologies

- Kotlin
- Android Studio
- Jetpack Compose
- Android WebView

---

# Project Structure

```text
webview-wrapper/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
├── gradle/
└── build.gradle.kts
```

---

# Running the Project

1. Start your local web application (default: `http://10.0.2.2:5173`).
2. Open the project in Android Studio.
3. Build and run the app on an emulator or Android device.

> **Note:** `10.0.2.2` is the special address Android emulators use to access the host machine's localhost.

---

# Concepts Demonstrated

- Embedding web content with `WebView`
- Integrating `WebView` with Jetpack Compose
- Loading local development servers
- Basic Android application structure

---

# Development Status

| Component | Status |
|-----------|--------|
| WebView Integration | Complete |
| Jetpack Compose UI | Complete |
| Local Development Support | Complete |

---

# Purpose

This repository serves as a lightweight proof of concept for packaging a web application inside a native Android app using WebView. It provides a foundation that can be expanded into a production-ready mobile wrapper.
