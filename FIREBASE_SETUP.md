# Firebase setup for WsIRS

1. Create a Firebase project at https://console.firebase.google.com/.
2. In Build > Authentication > Sign-in method, enable Anonymous sign-in.
3. In Build > Firestore Database, create a database.
4. In Project settings > General, add a Web app and copy the Firebase config.
5. Paste the config into `firebase-config.js`.
6. In Firestore Database > Rules, paste the contents of `firestore.rules` and publish.
7. Commit and push `firebase-config.js`.

After GitHub Pages redeploys, open the teacher page and scan the QR code from a different device. When the teacher changes the active question, the student page should update automatically.
