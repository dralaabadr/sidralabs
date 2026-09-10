# Sidra Labs - Progressive Web App (PWA)

نسخة جاهزة من موقع معامل سيدرا للتحاليل الطبية، محولة إلى **Static + PWA** عشان تشتغل على GitHub Pages وتتثبت كأبلكيشن على الموبايل.

## الملفات
- `index.html` → الصفحة الرئيسية (ثابتة)
- `manifest.json` → إعدادات الـ PWA
- `sw.js` → Service Worker للـ offline
- `offers/` → صور العروض
- `logo.png` / `cover.jpg` / `iso.png`

## طريقة الرفع على GitHub Pages

1. اعمل Repository جديد على GitHub (مثلاً `sidralabs` أو `sidralabs.github.io`)
2. ارفع كل محتويات الفولدر ده (مش الفولدر نفسه)
3. روح لـ **Settings → Pages**
4. اختار Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)`
5. بعد دقايق الموقع هيشتغل على:
   - `https://USERNAME.github.io/REPO_NAME/`
   أو لو عملت `USERNAME.github.io` هيشتغل على الدومين الرئيسي

## تثبيت كأبلكيشن (PWA)

### على أندرويد (Chrome):
- افتح الموقع
- هتظهر رسالة "Add to Home Screen" أو من القائمة ← "تثبيت التطبيق" / "Add to Home screen"

### على آيفون (Safari):
- افتح الموقع
- اضغط Share ← "Add to Home Screen"

بعد التثبيت هيفتح زي أي أبلكيشن بدون شريط المتصفح.

## ملاحظات مهمة
- لوحة التحكم القديمة (`offers.php`) اتشالت لأن GitHub Pages مش بيدعم PHP.
- عشان تضيف أو تحذف عروض جديدة: ارفع/احذف الصور من فولدر `offers/` على GitHub، وبعدين حدث الـ `index.html` (أو ابعتلي وأعدلها).
- لو عايز دومين خاص (مثل sidralaboratory.com) تقدر تربطه من إعدادات GitHub Pages.

## تحديث الصور لاحقاً
لو ضفت صور جديدة في `offers/`، لازم تضيفها كمان جوا `index.html` في قسم العروض عشان تظهر.
