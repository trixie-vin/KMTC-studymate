# KMTC StudyMate — phone-friendly PWA starter

This folder contains the KMTC StudyMate browser prototype prepared as a Progressive Web App (PWA) starter.

## Files
- `index.html` — prototype screens, sample notes, practice questions and quiz
- `manifest.webmanifest` — app name, launch mode and icon references
- `service-worker.js` — caches the app shell for repeat/offline loading
- `icons/` — app icons

## Important limitations
- This is a prototype, not a full production system or a native Kotlin app.
- Sample questions are original practice material, not official KMTC past papers.
- The demo does not yet have user accounts, cloud sync, admin content uploads, or a verified content database.
- Offline caching needs the site to be served over HTTPS and opened at least once online.
- Test on several Android devices before sharing widely.

## Phone-only next steps
1. Extract this ZIP on your phone.
2. In your mobile browser, create a repository on GitHub and upload the files so `index.html` is at the repository root.
3. In the repository settings, enable GitHub Pages for the main branch/root. Wait for the public HTTPS website URL.
4. Open the published website on your phone and test Notes, Papers, and Quiz.
5. Open PWABuilder.com, enter the published HTTPS URL, and use its Android packaging flow. Follow the packaging instructions and download the generated test APK / Play Store AAB when available.
6. Install and test the APK. Keep the signing key and credentials safe if you create them.
7. Before public release, add a privacy policy, verify content rights and accuracy, test accessibility/offline behaviour, and complete Google Play Console requirements.

Do not upload private student data, copyrighted exam papers without permission, passwords, or secret keys to a public repository.
