# uganda-2026-github-pages

Zak's Uganda 2026 digital travel archive with cross-device cloud sync.

## Files
- `index.html` — website
- `firebase-config.js` — add your Firebase keys here
- `firestore.rules` — copy these rules into Firebase Firestore Rules

## Important
GitHub Pages can host the website, but it cannot run a backend database by itself.
This package uses Firebase Authentication + Firestore as the small backend database.

## Setup Firebase
1. Go to Firebase Console
2. Create a project: `uganda-2026-archive`
3. Add a Web App
4. Copy the Firebase config values into `firebase-config.js`
5. Go to Authentication → Sign-in method → enable Email/Password
6. Go to Firestore Database → Create database
7. Go to Rules and paste the contents of `firestore.rules`
8. Publish rules
9. Upload all files to your GitHub repo root:
   - index.html
   - firebase-config.js
   - firestore.rules
   - README.md
10. Commit changes

After the site loads, click `Cloud Sync`, create an account, and your progress will sync across phone and desktop.
