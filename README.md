# FlutterBiometricAuth

A secure and user-friendly Flutter application that leverages local biometric authentication for seamless login. Built with the `local_auth` plugin, this app enables users to authenticate using fingerprint or face recognition, eliminating the need for passwords.

![App Screenshot](https://example.com/flutter-biometric-auth-screenshot.png)

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Features
- **Biometric Authentication**: Supports fingerprint and Face ID for secure, password-free login.
- **Cross-Platform Compatibility**: Runs smoothly on Android and iOS devices with biometric capabilities.
- **Minimalist Design**: Clean and intuitive UI for an enhanced user experience.
- **Local Authentication**: No server-side dependencies; authentication is handled securely on the device.
- **Robust Error Handling**: Gracefully manages unsupported devices or failed authentication attempts.

## Screenshots
| Login Screen | Biometric Prompt | Success Screen |
|--------------|------------------|----------------|
| ![Login Screen](https://example.com/flutter-login-screen.png) | ![Biometric Prompt](https://example.com/biometric-prompt.png) | ![Success Screen](https://example.com/auth-success.png) |

*Note*: Replace the placeholder image URLs above with actual links to your app’s screenshots (e.g., hosted on GitHub, Imgur, or another platform).

## Installation

### Prerequisites
- Flutter SDK (version 3.0.0 or higher)
- Dart SDK
- Android Studio or Xcode for emulator/device testing
- A device with biometric capabilities (fingerprint or Face ID)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ARK1998/flutter_biometric_auth.git
   cd flutter_biometric_auth
   ```

2. **Install Dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the App**:
   ```bash
   flutter run
   ```

Ensure your device or emulator supports biometric authentication. For Android, enable biometric settings; for iOS, configure Face ID or Touch ID.

## Usage
1. Launch the app on your device.
2. On the login screen, tap the "Authenticate" button.
3. Follow the biometric prompt (fingerprint or Face ID) to authenticate.
4. Upon successful authentication, you’ll be directed to a success screen.
5. If the device lacks biometric support or authentication fails, an error message will guide you.

## Dependencies
The app relies on the following Flutter package:
- `local_auth: ^2.1.0` - Handles biometric authentication for Android and iOS.

Add it to your `pubspec.yaml`:
```yaml
dependencies:
  flutter:
    sdk: flutter
  local_auth: ^2.1.0
```

## Contributing
We welcome contributions to enhance **FlutterBiometricAuth**! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request on [GitHub](https://github.com/ARK1998/flutter_biometric_auth).

Please ensure your code adheres to the Flutter style guide and includes relevant tests.

## License
This project is licensed under the BSD 3-Clause License. See the [LICENSE](LICENSE) file for details.

## Author
Created by [Muhammad Rafey Khan](https://github.com/ARK1998).

---

Built with ❤️ using Flutter. For questions or support, open an issue on the [GitHub repository](https://github.com/ARK1998/flutter_biometric_auth).