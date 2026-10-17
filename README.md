# Jihad HayDay Bot

Android build workspace for the Hay Day automation project.

## Automatic APK build

GitHub Actions checks out the public upstream source `elderofleader/HayDayBot`, builds the Android debug APK with JDK 17 and Gradle 8.4, and uploads the APK as a workflow artifact.

1. Open the **Actions** tab.
2. Select **Build Jihad HayDay Bot APK**.
3. Open the latest successful run and download the **Jihad-HayDay-Bot-debug** artifact.
4. Extract the downloaded ZIP to get the APK.

The source code is currently built from the upstream repository; this repository does not yet contain a full copied fork of that source. The APK is a debug build, not a signed release APK. Android Accessibility and screen-capture permissions must be enabled by the user on the device.
