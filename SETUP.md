# CareSync — Setup Guide

## Quick Start

```bash
git clone https://github.com/yourusername/caresync.git
cd caresync
flutter pub get
flutter run
```

## Platform-Specific Notes

### Android
- Requires Android SDK 21+ (Android 5.0)
- Add Google Maps API key to `android/app/src/main/AndroidManifest.xml` for maps features

### iOS
- Requires iOS 12.0+
- Run `cd ios && pod install` if you encounter build errors
- Add Google Maps API key to `ios/Runner/AppDelegate.swift` for maps features

### Web
- Run `flutter run -d chrome` for local dev
- Build with `flutter build web`

## Google Maps Setup (Optional)
Maps features are stubbed — to activate:
1. Create a project at [Google Cloud Console](https://console.cloud.google.com)
2. Enable Maps SDK for Android/iOS
3. Add your API key to the respective platform config files

## Known Issues
- Maps integration is currently placeholder and requires API keys
- Backend integration is demo only — all data is in-memory
