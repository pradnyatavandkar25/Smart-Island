# Smart-Island

This repository was prepared to be GitHub-ready by adding a CI workflow and helpful files.

## What I added
- `.github/workflows/android.yml` — GitHub Actions workflow that builds the app with Gradle (JDK11).
- `.gitignore` — common Android ignores.
- `README.md` — this file.

## How to run locally
1. Open the project in Android Studio.
2. Let Gradle sync and install required SDK components.
3. Run the app on an emulator or device.

## Notes
- If your project uses a specific Gradle or Android Gradle Plugin version, confirm `gradle-wrapper.properties` and `build.gradle` settings.
- The workflow runs `./gradlew assembleDebug` — ensure `gradlew` is present and executable.
