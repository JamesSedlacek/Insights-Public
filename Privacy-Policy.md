# Privacy Policy

**Effective Date:** 05/16/2025

*Insights for App Store Connect* ("the App") respects your privacy. This Privacy Policy explains how your data is handled when using the App.

## 1. Data Storage

The App stores data **locally on your device**. No data is transmitted to any external server.

- **UserDefaults and FileManager**: Used to cache non-sensitive app data to improve performance and user experience.
- **Keychain (via [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess))**: Securely stores your App Store Connect API Key credentials on your device. This information is never transmitted to any third-party service or external server.

## 2. Authentication

The App uses the [Swift-JWT](https://github.com/Kitura/Swift-JWT) library to generate JSON Web Tokens for authenticating with the App Store Connect API. Authentication is performed **locally**, and API credentials are securely managed using Keychain.

## 3. No Analytics or Tracking

The App does **not** collect analytics, usage data, or personally identifiable information. No data is shared with third parties.

## 4. No Internet-Based Backend

The App runs entirely on-device. It does not communicate with any backend server owned or operated by the developer.

## 5. No In-App Purchases

There are currently no in-app purchases available in the App.

## 6. Your Responsibility

You are responsible for managing your API keys and ensuring they are not shared with others. If you uninstall the App, your cached data and stored credentials will be removed from your device.

---

If you have any questions about this Privacy Policy, feel free to contact the developer at support@sedlaceksolutions.com.
