JAGESH ELECTRONIC V25 - Firebase Cloud Ready

Included:
- index.html : V25 app with Firebase Email/Password login and Firestore Cloud Sync
- jagesh-original-logo.png : original V25 logo asset
- firestore.rules : user-isolated Firestore rules

Firebase project configured in index.html:
projectId = jagesh-electronic

Cloud data path used by the app:
users/{Firebase Auth UID}/app/appData

IMPORTANT - ONE FINAL FIREBASE CONSOLE STEP
1. Open Firebase Console for jagesh-electronic.
2. Go to Build -> Firestore Database -> Rules.
3. Replace the current rules with the contents of firestore.rules.
4. Click Publish.

Authentication:
Email/Password is expected to be enabled. The app has Login and Create New Account screens.

Existing V25 local data:
On the first login of an account, if that account has no Cloud data and the device has old V25 local data, the app asks whether to import that old data into the logged-in account. This avoids automatically mixing the old device data into a second technician account.

Important:
The app must be served from HTTPS / Firebase Hosting (or another secure origin) for Firebase web authentication and the existing GPS feature to work reliably.
