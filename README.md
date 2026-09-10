# Sidra Labs - Android APK (Capacitor)

تحويل موقع معامل سيدرا للتحاليل الطبية إلى تطبيق أندرويد حقيقي (WebView) باستخدام Capacitor.

**بدون PWA** – التطبيق يعمل كتطبيق أندرويد عادي.

## الملفات المهمة
- `index.html` + الصور + `offers/`
- `capacitor.config.json`
- `package.json`
- `.github/workflows/build-apk.yml` → يبني الـ APK تلقائياً

## طريقة الحصول على الـ APK

### الطريقة الأسهل (موصى بها):
1. ارفع فولدر `offers/` كامل على الريبو (لو مش موجود).
2. روح على تبويب **Actions** في الريبو.
3. اختار workflow اسمه **Build Android APK**.
4. اضغط **Run workflow** → Run.
5. استنى 3-6 دقايق.
6. بعد ما يخلص، هتلاقي **Artifacts** تحت → حمل ملف `sidralabs-apk`.
7. فك الضغط وثبّت الـ APK على الموبايل.

### ملاحظات
- الـ APK اللي بيطلع Debug (مناسب للاختبار والتوزيع الخاص).
- لو عايز APK موقع (Signed) لرفع على Google Play، قولي وأعدل الـ workflow.

## الرابط
https://github.com/dralaabadr/sidralabs
