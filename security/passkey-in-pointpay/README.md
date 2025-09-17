---
description: New option to keep your funds secure and safe
icon: key
---

# PassKey in PointPay

🔐 What is Passkey?

Passkey is a modern, passwordless authentication method. Instead of entering a password, you log in using biometrics: Face ID, fingerprint, PIN, or system password — depending on your device. It's secure, convenient, and supported by most modern platforms.

***

### 🚪 How Passkey Login Works

Depending on whether you have Passkey set up and your device supports it, the login experience may vary:

#### ✅ If Passkey is set up on your account:

* Device supports Passkey → native biometric login is triggered (Face ID / Touch ID / Windows Hello).
* Device does not support Passkey → standard login form is shown: email + password + 2FA.
* Passkey is not installed on this device → email + CAPTCHA are shown, then you can:
  * scan a QR code from another device,
  * switch to the traditional login method.

#### ❌ If Passkey is not set up:

* Login follows the standard flow: email + password + 2FA.

***

### ➕ How to Add a Passkey in PointPay

1. Go to Account Settings → Security tab → Passkey section.
2. If 2FA is not enabled, the system will prompt you to enable it first.
3. Once 2FA is active, you’ll see a screen explaining Passkey benefits.
4. Confirm your action:
   * enter the code from your email,
   * enter your 2FA code.
5. Your device will then trigger the system-native Passkey setup window.
6. Once confirmed, the Passkey is stored on your device and linked to your account.

***

### ✏️ Changing the Device Name

* When a Passkey is added, your device is labeled automatically (e.g., iOS – iPhone).
* You can rename it manually by clicking the pencil icon next to the device in your Passkey settings.

***

### 🛑 Disabling Passkey

1. Open Passkey settings.
2. Click "Disable".
3. Confirm using:
   * email code,
   * 2FA code.
4. On your next login, the classic flow (email + password + 2FA) will be used by default.

***

### 🔁 Passkey Synchronization Between Devices

| Platform  |                                                                              |
| --------- | ---------------------------------------------------------------------------- |
| iOS/macOS | iCloud Keychain — Passkey is available on all devices with the same Apple ID |
| Android   | Google Account Passkeys — available across all linked Android devices        |
| Windows   | Google Passkey or Windows Hello — both offer secure local storage options    |

Cross-platform login: If you're on Windows and scan a QR code using your iPhone, the login will be confirmed via iPhone biometrics.

***

### ✅ "Remember me" option&#x20;

* If you check Remember Me:
  * 2FA and email code are skipped on the next login.
  * The setting lasts 30 days.
* After that, you'll need to check it again and re-confirm with codes.
