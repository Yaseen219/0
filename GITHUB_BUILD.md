# Chess Master — GitHub APK build

1. Create a GitHub repository.
2. Upload the **contents** of this project ZIP, not the ZIP itself. The repository root must contain `settings.gradle.kts`, `build.gradle.kts`, `gradle.properties`, and `app/`.
3. Open **Actions**.
4. Select **Build Chess Master APK**.
5. Tap **Run workflow**.
6. Wait for the green check.
7. Open the completed workflow run and download **ChessMaster-debug-apk**.
8. Extract the downloaded artifact and install the APK on the phone.

This produces a debug APK for testing. A signed AAB is required for Google Play release.
