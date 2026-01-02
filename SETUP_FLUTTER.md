# Car Wash Booking App - Setup Instructions

## ⚠️ Flutter Installation Required

The Flutter SDK is not currently installed on your system. To run this project, please follow these steps:

### 1. Install Flutter

**For Windows:**

1. Download Flutter SDK from: https://flutter.dev/docs/get-started/install/windows
2. Extract to a folder (e.g., `C:\flutter`)
3. Add Flutter to your system PATH:
   - Open Environment Variables (Win + R → `sysdm.cpl`)
   - Edit System variables
   - Add `C:\flutter\bin` to PATH

4. Open new PowerShell and verify:
```powershell
flutter --version
```

### 2. Install Flutter Doctor Dependencies

```powershell
flutter doctor
```

This will show you what else needs to be installed.

### 3. Install Project Dependencies

Once Flutter is installed, run:

```powershell
cd C:\CarMaint
flutter pub get
```

### 4. Run the App

```powershell
# For Android
flutter run

# For iOS (Mac only)
flutter run -d iPhone

# For Web
flutter run -d chrome
```

## 📋 System Requirements

- **Windows 10+**
- **Android Studio** (for Android development) or **Xcode** (for iOS)
- **VS Code** (recommended) with Flutter and Dart extensions
- **Minimum 1.5 GB free disk space**

## 🔧 VS Code Extensions (Recommended)

- Flutter (ID: Dart-Code.flutter)
- Dart (ID: Dart-Code.dart-code)

## 📚 Project Ready

✅ All project files are created and ready:
- Main app structure in `lib/main.dart`
- 4 screens: Home, Booking, My Bookings, Profile
- Models for Services and Bookings
- Responsive UI with Material Design
- `pubspec.yaml` configured with all dependencies

Once Flutter is installed, the app will be ready to run!
