# Dark GPT

مشروع Dark GPT بواجهة HTML وسيرفر Node.js.

## التشغيل

1. ثبّت Node.js.
2. افتح مجلد المشروع.
3. نفّذ:
   npm install
4. انسخ `.env.example` إلى `.env`.
5. ضع مفتاح Gemini في:
   GEMINI_API_KEY=...
6. شغّل:
   npm start
7. افتح:
   http://localhost:3000

## ملاحظات الأمان

- مفتاح API موجود على السيرفر داخل `.env` وليس داخل HTML.
- لا ترفع ملف `.env` إلى GitHub.
- يمكن تغيير الشخصية من `SYSTEM_INSTRUCTION` داخل `server.js`.
- يمكن تغيير النموذج من `GEMINI_MODEL` داخل `.env`.
