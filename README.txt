Khaled × Menna
================
الملفات:
- index.html: اللعبة
- admin.html: صفحة خالد السرية
- song.mp3: الأغنية التي أرسلتها
- supabase.sql: إنشاء قاعدة البيانات والسياسات

مهم:
النسخة الحالية مربوطة بـ Supabase: عند إنهاء اللعبة يتم إرسال الإجابات إلى جدول game_answers، وصفحة admin تقرأ الإجابات بعد تسجيل دخول حساب الإدارة.

إعداد Supabase:
1. أنشئ مشروعًا في Supabase.
2. SQL Editor -> الصق supabase.sql -> Run.
3. Authentication -> Users -> أنشئ حساب الإدارة.
4. Project Settings -> API -> انسخ Project URL وanon/public key.
5. ضع القيم في admin.html بدل PUT_YOUR_SUPABASE_URL_HERE وPUT_YOUR_SUPABASE_ANON_KEY_HERE.
6. لا تستخدم service_role key داخل ملفات الموقع.
