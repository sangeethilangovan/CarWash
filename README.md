# Car Wash Booking App

A cross-platform mobile application for booking car wash services, built with Flutter.

## 📱 Features

- **Browse Services** - View available car wash packages with pricing and details
- **Easy Booking** - Simple and intuitive booking interface
- **Time Slot Selection** - Choose preferred date and time slots
- **My Bookings** - Track and manage all your bookings
- **User Profile** - Manage account information and preferences
- **Responsive Design** - Works seamlessly on iOS and Android

## 🏗️ Project Structure

```
lib/
├── main.dart              # App entry point and navigation
├── models/
│   ├── car_wash_service.dart   # Service model
│   └── booking.dart            # Booking model
└── screens/
    ├── home_screen.dart        # Home/browse services
    ├── booking_screen.dart     # Create new booking
    ├── my_bookings_screen.dart # View past bookings
    └── profile_screen.dart     # User profile
```

## 🛠️ Installation

### Prerequisites
- Flutter SDK (v3.0.0 or higher)
- Dart (v3.0.0 or higher)
- Android Studio or Xcode

### Setup Steps

1. **Clone/Navigate to Project**
```bash
cd C:\CarMaint
```

2. **Get Dependencies**
```bash
flutter pub get
```

3. **Run the App**

   **For Android:**
   ```bash
   flutter run
   ```

   **For iOS:**
   ```bash
   flutter run -d iPhone
   ```

   **For Web:**
   ```bash
   flutter run -d chrome
   ```

## 📦 Dependencies

- `provider` - State management
- `http` - API calls
- `intl` - Date/time formatting
- `google_fonts` - Custom fonts
- `firebase_core`, `firebase_auth`, `cloud_firestore` - Backend services
- `geolocator`, `google_maps_flutter` - Location services

## 🎯 Key Screens

### Home Screen
- Display popular car wash services
- Service cards with pricing and duration
- Quick access to booking

### Booking Screen
- Select service from dropdown
- Choose preferred date
- Select time slot
- Enter car details
- Confirm booking

### My Bookings Screen
- View all bookings with status
- Cancel confirmed bookings
- Rebook completed services
- Booking history

### Profile Screen
- View user information
- Manage settings
- Payment methods
- Help & Support
- Logout option

## 🚀 Development

To extend the app:

1. **Add New Services** - Modify `home_screen.dart`
2. **Implement Backend** - Connect to Firebase or REST API
3. **Add Authentication** - Implement Firebase Auth
4. **Location Services** - Integrate Google Maps for service locations
5. **Payments** - Add Stripe or PayPal integration

## 📝 License

MIT License - Free to use and modify
