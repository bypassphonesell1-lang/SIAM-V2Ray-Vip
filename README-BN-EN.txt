# SIAM V2Ray Vip Android project

This project packages the current HTML login screen inside a simple Android WebView app.

## Build an APK with GitHub Actions (free tier subject to GitHub limits)
1. Create a new GitHub repository.
2. Upload all files and folders from this project ZIP to the repository root.
3. Open the repository's **Actions** tab.
4. Run **Build SIAM V2Ray Vip APK** (or wait for the push build).
5. Open the successful workflow run, scroll to **Artifacts**, and download `SIAM-V2Ray-Vip-debug-APK`.
6. Extract the downloaded artifact ZIP and install `app-debug.apk` on your Android phone.

## Important limitations
- This APK is only a packaged version of the current login-page design.
- The username/password check is inside the app and is NOT secure production authentication.
- It does not create customer accounts, show live Saudi carrier packages, or connect to a V2Ray/Xray VPN server.
- `MY APPS` has no download URL yet.
- Do not use this for real customer accounts or store sensitive credentials until a secure backend and VPN server are configured.
