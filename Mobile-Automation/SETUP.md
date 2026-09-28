# Appium Setup

1. Install Java 17+, Maven, Android SDK, and Appium 2.
2. Start an Android emulator or connect a test device.
3. Install the Kredily APK on the test device.
4. Start Appium server.
5. Inspect the APK with Appium Inspector to obtain resource IDs/accessibility IDs/XPaths.
6. Replace the placeholder locators and driver capabilities in the test code.
7. Run `mvn test`.
8. Save the generated execution report under this folder.

Do not commit passwords or other credentials into source code.
