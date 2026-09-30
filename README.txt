HOW TO GET THE APK (no Android Studio needed)
1. Create a free account at github.com and make a new repository.
2. Upload ALL files/folders in this project (including the hidden .github folder) to it.
3. Open the "Actions" tab -> "Build APK" -> wait ~5 minutes for a green tick.
4. Open the finished run -> Artifacts -> download "GasketPathBuilder-apk" -> unzip -> app-debug.apk
5. Copy app-debug.apk to your phone, tap it, allow "Install unknown apps", install.

Or, with Android Studio: npm install && npx cap add android && npx cap sync && npx cap open android
