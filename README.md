# Rei Super Kanji Trainer

<img src="icon-192.png" width="120" alt="Rei Super Kanji Trainer">

A personal, self-contained spaced-repetition trainer for locking in reading and writing of Tokyo Gas billing kanji and vocab. Warm mnemonic stories, honest grading, and a due pile you can clear in five focused minutes.

Live: https://reiby-kraken.github.io/rei-kanji/

The hosted build is password protected. The page content is encrypted in the source (AES-256-GCM with a key derived by PBKDF2-SHA256) and only your password decrypts it in your browser via the Web Crypto API. Open it over HTTPS. On iPhone, use Add to Home Screen for an app-like icon and name.

## Cross-device sync (optional)

Progress always saves in your browser on the device you study on. To sync your phone and laptop, sign in with Google:

1. Open the app, unlock it, and find "Sync across devices".
2. Tap "Sign in with Google" and pick your account.
3. Do the same on your other device with the same account.

After that your reps sync automatically: it pulls when you open the app and pushes a few seconds after each card, with live updates across devices. Export and Import remain as a manual backup.

## Privacy notes

- The app content is encrypted at rest in this public repo; only the password unlocks it in the browser.
- The password is short, so treat this as a light gate rather than strong security.
- Sync uses your own Google account through Firebase, and your progress is stored under your account's user id. Your synced data is not behind the app password.
