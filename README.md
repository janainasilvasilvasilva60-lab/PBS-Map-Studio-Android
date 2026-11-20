# PBS Map Studio Android wrapper (0.26.13)

Android WebView wrapper for the source HTML editor.


## Build in GitHub Actions
1. Upload the contents of this project to a GitHub repository (root files, not the enclosing folder).
2. Open **Actions** tab.
3. Select **Build PBS Map Studio APK**.
4. Choose **Run workflow** and confirm.
5. Download the artifact `PBS-Map-Studio-debug-apk` after the run succeeds.


This wrapper is a packaging baseline, not a fully tested release. The editor's import/export and WebGL behavior on Android must be validated. The HTML source currently references an `assets` folder that was absent from the supplied ZIP; this may affect visuals or features.
