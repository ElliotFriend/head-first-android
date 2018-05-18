- Versions of Android have a version number, API level, and code name.
- Android Studio is a special version of IntelliJ IDEA that interfaces with the
  Android Software Development Kit (SDK) and the gradle build system.
- A typical Android app is comprised of activities, layouts, and resource files.
- Layouts describe what your app looks like. They're held in the
  *app/src/main/res/layout* folder
- Activities decscribe what your app does, and how it interacts with the user.
  The activities you write are held in the *app/src/main/java* folder.
- *strings.xml* contins string name/value pairs. It's used to separate out text
  values from the layouts and activities, and supports localization.
- *AndroidMainfest.xml* contains information about the app itself. It lives in
  the *app/src/main* folder.
- An AVD is an Android Virtual Device. It runs the Android emulator and mimics a
  physical Android device.
- An APK is an Android application package. It's like a JAR file for Android apps,
  and contians your app bytecode, libraries, and resources. You install an app
  on a device by installing the APK.
- Android apps run in separate processes using the Android runtime (ART).
- `RelativeLayout` is used to place GUI components in relative positions in a
  layout.
- The `TextView` element is used for displaying text.