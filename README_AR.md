# استوديو طاهر — مشروع Android APK

هذا مشروع Android بسيط يغلّف نسخة الويب الحالية داخل WebView، ويحمّل:
https://tahir-voice-studio-next.tahir-voice-studio.workers.dev/

## بناء APK عبر GitHub Actions
1. أنشئ مستودع GitHub جديداً وارفع محتويات هذا المجلد إليه.
2. افتح تبويب Actions في المستودع.
3. شغّل workflow باسم Build Tahir Voice Studio APK (أو انتظر انتهاء البناء بعد push إلى main).
4. افتح نتيجة التشغيل ثم نزّل Artifact باسم `tahir-voice-studio-debug-apk`.
5. فك الضغط وثبّت `app-debug.apk` على Android.

هذه نسخة Debug للتثبيت والاختبار. إصدار Play Store يحتاج توقيع Release ومفتاح توقيع خاصاً.
