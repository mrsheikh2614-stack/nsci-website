NSCI WEBSITE - FINAL GITHUB VERSION

Files:
- index.html
- assets/nsci-poster.png
- assets/nsci-logo.png

IMPORTANT:
1. Open index.html and replace PASTE_YOUR_API_KEY and PASTE_YOUR_APP_ID with the Firebase Web App config from Firebase Console > Project settings > Your apps.
2. Firestore collection: members
3. Firestore stats document: stats/summary with memberCount (number). The page reads only this public count document; member records are not displayed publicly.
4. Use the Firestore rules supplied separately so visitors can create a member and the count updates atomically, while existing member data stays private.
5. Upload the whole structure to GitHub Pages. Do not upload the ZIP itself as the site.
