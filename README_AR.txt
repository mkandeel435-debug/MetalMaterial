تطبيق دليل تحليل المعادن والمسبوكات — مشروع Android

هذا المشروع يغلّف ملف HTML الأصلي داخل تطبيق أندرويد باستخدام WebView.
تم نسخ الملف الأصلي كما هو إلى:
app/src/main/assets/index.html
وبذلك تبقى بياناته ووظائف البحث الموجودة فيه كما هي، ولا يحتاج التطبيق إلى الإنترنت لتشغيل الصفحة المحلية.

طريقة إنشاء APK:
1) ثبّت Android Studio على كمبيوتر.
2) افتح Android Studio واختر Open، ثم اختر مجلد MetalMaterialAndroid.
3) انتظر اكتمال Gradle Sync وثبّت Android SDK Platform 35 إذا طُلب منك.
4) من القائمة Build اختر Build Bundle(s) / APK(s) ثم Build APK(s).
5) بعد انتهاء البناء، اضغط Locate في إشعار البناء للوصول إلى ملف APK.

معلومات المشروع:
- اسم التطبيق: دليل تحليل المعادن والمسبوكات
- Application ID: com.example.metalmaterial
- الحد الأدنى: Android 6.0 (API 23)
- النسخة: 1.0

ملاحظة: هذا أرشيف مشروع Android Studio وليس ملف APK مُجمّعًا. بيئة الإنشاء الحالية لا تحتوي على Android SDK أو Gradle، لذلك لم أتمكن من إخراج APK جاهز هنا.
