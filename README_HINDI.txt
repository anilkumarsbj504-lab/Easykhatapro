EASY KHATA PRO — ANDROID PROJECT

इस ZIP में Easy Khata Pro का Android Studio source project है।
यह अभी APK नहीं है। APK बनाने के लिए Android build environment चाहिए।

फ़ाइलें:
- app/src/main/assets/index.html : ऐप का HTML संस्करण
- app/src/main/java/com/easykhata/pro/MainActivity.java : Android WebView स्क्रीन
- Gradle project files : Android Studio build setup

APK बनाने का सामान्य तरीका:
1. ZIP को extract करें।
2. Android Studio में Extracted EasyKhataPro फ़ोल्डर खोलें।
3. Gradle sync पूरा होने दें।
4. Build > Build APK(s) चुनें।
5. APK app/build/outputs/apk/debug/app-debug.apk में बनेगा।

ध्यान दें:
- यह शुरुआती WebView wrapper है, पूर्ण native Android app नहीं।
- डेटा इस HTML ऐप के local browser/WebView storage में रहता है। ऐप uninstall या app data clear करने से डेटा मिट सकता है।
- महत्वपूर्ण हिसाब का Backup/Export नियमित करें।
- Google Play पर publish करने के लिए अलग signing, testing और store requirements होंगी।
