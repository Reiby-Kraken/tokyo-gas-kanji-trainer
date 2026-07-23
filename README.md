# Rei Super Kanji Trainer

<img src="icon-192.png" width="120" alt="Rei Super Kanji Trainer">

A personal, self-contained spaced-repetition trainer for locking in reading and writing of Tokyo Gas billing kanji and vocab. Warm mnemonic stories, honest grading, and a due pile you can clear in five focused minutes.

Live: https://reiby-kraken.github.io/tokyo-gas-kanji-trainer/

The hosted build is password protected. The page content is encrypted in the source (AES-256-GCM with a key derived by PBKDF2-SHA256) and only your password decrypts it in your browser via the Web Crypto API. Open it over HTTPS. On iPhone, use Add to Home Screen for an app-like icon and name.

## Cross-device sync (optional)

Progress saves in your browser. To sync phone and laptop, use your own private GitHub gist:

1. Create a classic GitHub token with only the "gist" scope at github.com/settings/tokens.
2. Open the app, unlock it, and find "Sync across devices".
3. First device: paste the token, tap Enable sync, copy the sync code.
4. Other devices: paste the code, tap Link this device.

After that it pulls when you open the app and saves a few seconds after each card. Export and Import remain as a manual backup.

## Privacy notes

- The app content is encrypted at rest in this public repo; only the password unlocks it in the browser.
- The password is short, so treat this as a light gate rather than strong security.
- Sync progress lives in your own private gist. Anyone holding your sync code (it contains your token) can read and write it, so keep the code private. The gist itself is not behind the app password.
