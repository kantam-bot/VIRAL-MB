# VIRAL MB — Android starter

This is an Android Kotlin + Jetpack Compose starter with a GitHub Actions workflow
that builds a **debug APK**.

## Upload to GitHub from a phone
Upload the project files and folders (not just this ZIP) into:
https://github.com/kantam-bot/VIRAL-MB

## Build APK
After the files are in the `main` branch:
1. Open the repository's **Actions** tab.
2. Select **Build VIRAL MB APK**.
3. Tap **Run workflow**, or wait for the workflow triggered by a push.
4. Open the successful run and download `VIRAL-MB-debug-apk`.

## Important project status
This is a starter/demo, **not a production app**. Campaigns are held only in app memory
and are not shared with other users. It does not yet implement Firebase email/SMS
authentication, cloud database, recommendation engine, moderation, production
analytics, privacy/legal flows, or signed release APK. Those features must be
implemented, configured, and tested before public launch. No APK build has been
run or verified from this package yet.
