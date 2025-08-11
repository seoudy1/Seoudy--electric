SEOUDY ELECTRIC - Admin-only (Dark theme, Arabic)
------------------------------------------------
محتويات الحزمة:
- صفحات عامة: index.html, services.html, contact.html
- لوحة مشرف: /admin/index.html (عربية، داكنة) مربوطة بقيم Firebase المُضمنة
- مجلد assets يحتوي الشعار، البنر، الاعلان، favicon

خطوات سريعة للتشغيل بعد الرفع إلى Vercel:
1. افتح Firebase Console لمشروع seoudy-electric وتأكد من تفعيل:
   - Authentication (Email/Password)
   - Firestore
   - Storage
2. في Authentication > Users أنشئ مستخدماً بالإيميل: elmshrky666666@gmail.com وكلمة: asm1980ASM
3. ارفع المجلد على Vercel (Upload folder) أو إلى GitHub ثم استورد المشروع في Vercel.
4. بعد النشر افتح: https://<your-site>/admin/ وسجّل دخول بالمستخدم الذي أنشأته

قواعد أمان مقترحة (Firestore/Storage):
- السماح بالكتابة للـ authenticated users فقط.
- اضبط قواعد قواعد Firestore/Storage لتقييد الوصول بعد الاختبار.

إذا تريد أقدر أرافقك خطوة بخطوة لرفع الحزمة وضبط Firebase والقواعد.
