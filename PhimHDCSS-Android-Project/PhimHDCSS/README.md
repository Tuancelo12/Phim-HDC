# PhimHDCSS Android app

A simple Android WebView app that opens https://phimhdcss.com/.

## Build APK automatically with GitHub Actions

This project includes `.github/workflows/build-apk.yml` to build a debug APK in GitHub's cloud runner.

1. Create a repository on GitHub and upload the contents of this folder (the `PhimHDCSS` folder contents, not the outer folder).
2. Open the repository's **Actions** tab.
3. Select **Build PhimHDCSS APK** and click **Run workflow** (or push to `main`/`master`).
4. When it finishes, open the completed run and download the artifact named **PhimHDCSS-debug-apk**.
5. Extract the downloaded artifact; it contains `app-debug.apk`. Transfer it to your Android phone and install it. You may need to allow installs from that file manager.

This is a debug-signed APK for personal testing. It has not been built or tested in this environment.
