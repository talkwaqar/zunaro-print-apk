# Zunaro Print (Android APK)

Test build of **Zunaro Print**, a proof of concept for printing event tickets from an Android phone: scan the ticket's QR code, tap **Print**, and it prints on the printer attached to a laptop on the same Wi-Fi.

## Download

**[zunaro-print.apk](https://github.com/talkwaqar/zunaro-print-apk/releases/latest/download/zunaro-print.apk)** (about 41.5 MB, Android 7.0+)

## Install

1. Open the link above on your Android phone and download the APK.
2. Open the downloaded file and tap **Install**. Allow installs from your browser when Android asks.
3. This is a test build signed with a debug key, so Google Play Protect may warn about an unknown app. Tap **Install anyway** if you trust this source.

To remove it, long-press the app icon and tap **Uninstall**.

## Use

1. Start the Zunaro print agent on the laptop with the printer.
2. In the app, open **Settings**, set the agent URL to `http://<laptop-ip>:3000`, tap **Test connection**, then **Save**.
3. Tap **Scan ticket QR**, allow camera access, point the camera at the ticket, then tap **Print**.

This is a proof of concept, not a production release.
