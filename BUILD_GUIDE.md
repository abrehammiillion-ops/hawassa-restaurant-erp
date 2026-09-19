# Build Guide

## GitHub Pages
Upload everything in this folder to your GitHub repository. Keep `index.html` at the repository root.

## Android APK
Open `android-app` in Android Studio, allow Gradle sync, then use Build → Generate App Bundles or APKs → Generate APKs.

## Windows EXE
Open `windows-app` in Command Prompt/PowerShell:
`npm install`
`npm run dist`
The installer will be in `windows-app/dist/`.

The ZIP contains source projects; APK/EXE binaries require Android Studio or Electron build tools.
