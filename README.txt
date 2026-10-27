DAYBOOK ANDROID PROJECT

Android Studio project wrapping the Daybook HTML app in an Android WebView.
Includes Habit Tracker, Workout PR Tracker and Journal.

BUILD LOCALLY
1. Install Android Studio with Android SDK Platform 35 and JDK 17.
2. Open this folder in Android Studio and allow Gradle sync.
3. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK output: app/build/outputs/apk/debug/app-debug.apk

BUILD WITH GITHUB ACTIONS
1. Create a private GitHub repository and upload the contents of this folder to main.
2. Open Actions and run 'Build Daybook APK' (or push a commit).
3. Download the 'Daybook-debug-apk' artifact from the completed run.

NOTES
- Data is stored locally in the WebView browser storage.
- This is a debug APK project, not a Play Store release.
- Cloud sync, reminders and cross-device backup are not included yet.
