مشروع Neon Heart — نسخة ويب قابلة للنشر

تشغيله على جهازك:
1) ثبّت Python 3.11 أو 3.12.
2) افتح Terminal داخل مجلد المشروع.
3) نفّذ:
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   python app.py
4) افتح المتصفح على:
   http://127.0.0.1:5000

كيف تخليه عامًا للناس؟
- ارفع ملفات المشروع إلى مستودع GitHub.
- أنشئ Web Service على Render واربطه بالمستودع.
- Build Command: pip install -r requirements.txt
- Start Command: gunicorn app:app
- بعد اكتمال النشر ستحصل على رابط عام يستطيع الآخرون فتحه من الهاتف أو الكمبيوتر.

ملاحظات:
- هذه نسخة ويب: Python/Flask يشغّل الموقع، والأنيميشن مرسوم داخل المتصفح باستخدام JavaScript Canvas.
- زر Personalize يتيح تغيير الكتابة أثناء الاستخدام، وزر Replay يعيد بداية الحركة.
- لا ترفع كلمات مرور أو بيانات خاصة إلى مستودع عام.
