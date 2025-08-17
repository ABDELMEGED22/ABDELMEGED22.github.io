# Giedo digital marketing — موقع ديناميكي قابل للتحكم

هذا المشروع يوفّر موقعًا ثابتًا يُقدّم محتواه من Firebase Firestore، ولوحة إدارة (admin.html) للتحكم الكامل بالمحتوى (اسم الموقع، هاتف، باقات، منتجات، الباقة العالمية...). يمكن نشره على GitHub Pages (دومين مجاني username.github.io).

الخطوات السريعة للنشر:
1. افتح إعدادات مشروع Firebase وأنشئ مشروع جديد على https://console.firebase.google.com
2. فعّل Firestore (Native mode) وفعّل Authentication > Email/Password
3. انسخ إعدادات التهيئة (config) من صفحة إعدادات المشروع والصقها في firebase-config.js
4. عدّل قواعد Firestore بحيث يسمح بالكتابة فقط للمسؤولين (انظر الاقتراح داخل README الكامل في المستودع).
5. اذهب إلى https://github.com/ABDELMEGED22/ وافتح المستودع `ABDELMEGED22.github.io` لمعرفة الصفحة بعد نشر الملفات.

ملاحظة: ملف firebase-config.js يحتوي قيمًا افتراضية يجب استبدالها بقيم مشروعك. لتشغيل لوحة الإدارة بشكل آمن، أنشئ حساب مستخدم عبر Firebase Console أو استخدم زر إنشاء حساب في admin.html ثم حدّد قواعد Firestore لمنع التسجيل العام.
