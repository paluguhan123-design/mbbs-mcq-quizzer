# MBBS MCQ Quizzer — Subtopics Update

## Features
- Organize content as Subject › Chapter › optional Subtopic (for example Microbiology › Bacteriology › Tuberculosis). Each study section can hold its own MCQs.
- Existing flat chapters from the previous version remain available.
- Import MCQ images and separate answer-key images using OCR (Tesseract.js is loaded from a CDN, so internet is needed for OCR).
- Review/edit OCR output and answer-key matches before saving.
- Randomized practice, instant feedback, score/progress, and a persistent wrong-question list.
- Score history and JSON backup export/import.
- PWA manifest, service worker, and install icons.

## Install on Android
1. Extract this ZIP.
2. Host the folder on an HTTPS static host (for example GitHub Pages). Service workers/PWA installation generally do not work from a local `file://` path.
3. Open the hosted site in Chrome on Android.
4. Use Chrome menu → **Install app** or **Add to Home screen**.

## Important
- Data is stored in this browser on this device. Use **Export backup** before clearing browser data or changing devices.
- OCR may misread medical terms and answer keys; check every question on the review screen before saving.
- This is a client-side study tool, not a verified question-bank answer source.
- An Android APK has not been built yet; this package is the PWA/web app.


## Updating an already-hosted GitHub Pages app
1. Open your repository and upload the files from this ZIP, replacing the existing files when prompted.
2. Ensure index.html, manifest.webmanifest, sw.js, icon-192.png, and icon-512.png are in the repository root.
3. Commit the changes. Refresh the hosted site after GitHub Pages finishes publishing. If an older version remains cached, close the site and reopen it in Chrome, or clear the site cache.
