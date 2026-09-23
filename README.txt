Association of Geographers — Firebase-enabled website

Files:
index.html              Public website
admin.html              Admin login
admin-dashboard.html    Admin dashboard
firebase-config.js      Firebase Web App configuration
public-firebase.js      Public Firebase data connection
script.js               Menu interactions
style.css               Website styles
logo.jpg                Association logo

Firebase setup:
- Authentication: Email/Password enabled
- Realtime Database: Locked rules with admin UID
- Admin UID configured in admin-dashboard.html

Important:
1. Do not publish your admin password anywhere.
2. The Firebase web config is client-side configuration; database rules protect data.
3. Gallery currently uses public image URLs. Firebase Storage can be added later for direct uploads.
4. Financial/account records should be used only after reviewing rules and accounting workflow; this dashboard is not a banking/payment system.

GitHub Pages:
Upload all files to the repository root. Do not upload the ZIP itself.
Then Settings -> Pages -> Deploy from branch -> main -> /(root).
