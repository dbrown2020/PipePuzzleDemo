# PipePuzzleDemo (Android / Unity-style prototype in native Kotlin)

This is a tiny, installable Android demo (Jetpack Compose) that implements:
- Tap-to-rotate pipe tiles
- Flow propagation from Source
- Win = all sinks powered AND **no leaks anywhere**

## Build in Android Studio (recommended)
1. Install Android Studio (latest stable).
2. Open this folder as a project.
3. Let it download the Android Gradle Plugin + dependencies.
4. Ensure your Android SDK is installed (Android Studio will prompt).
5. Run on an emulator or device.

## Generate an APK
- Build > Build Bundle(s) / APK(s) > Build APK(s)
- The debug APK path will appear in the Build output.

## GitHub Actions (optional)
This repo includes a workflow that builds a debug APK and uploads it as an artifact.
