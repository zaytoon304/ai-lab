# خطة ترتيب أسماء الملفات - القاعدة الذهبية التفاعلية

الهدف: كل ملف يوضح وظيفته من اسمه فقط، بدون تكرار أسماء بين المجلدات.
**لا حذف لأي ملف — فقط إعادة تسمية (rename) بأمر git mv اللي يحافظ على المحتوى والتاريخ.**

## خطوات التنفيذ

- [x] نسخة احتياطية إضافية قبل البدء (git tag: `before-rename-cleanup`)
- [x] إعادة تسمية `app.js` (الجذر) ← `main.js`
- [x] إعادة تسمية `stories/app.js` ← `stories/stories-app.js`
- [x] إعادة تسمية `parent/dashboard.js` ← `parent/parent-dashboard.js`
- [x] إعادة تسمية `teacher/dashboard.js` ← `teacher/teacher-dashboard.js`
- [x] إعادة تسمية `teacher/analytics.js` ← `teacher/teacher-analytics.js`
- [x] إعادة تسمية `teacher/analytics.css` ← `teacher/teacher-analytics.css`
- [x] نقل `teacher.css` (الجذر) ← `teacher/teacher-panel.css`
- [x] إعادة تسمية `worksheets/generator.js` ← `worksheets/worksheets-generator.js`
- [x] إعادة تسمية `flashcards/generator.js` ← `flashcards/flashcards-generator.js`
- [x] إعادة تسمية `exams/generator.js` ← `exams/exams-generator.js`
- [x] تحديث كل الروابط في `index.html`
- [x] تحديث كل الروابط في `sw.js`
- [x] تشغيل أداة الفحص `npm run validate` — نجح بدون أخطاء
- [x] فتح الموقع محلياً بالمتصفح والتأكد إنه شغال (الرئيسية، لوحة المعلم، أوراق العمل، البطاقات، الاختبارات، القصص، لوحة ولي الأمر) — كل شيء يعمل بدون أي خطأ بالكونسول
- [ ] رفع التغييرات على GitHub (بانتظار تأكيد المستخدم)

## ملاحظات
- الملفات الباقية أسماؤها واضحة ومو مكررة، ما راح تتغير.
- كل خطوة تُختبر فوراً بعدها، ما ننتقل للي بعدها إلا لو الأولى نجحت.
