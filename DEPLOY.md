# 🚀 تعليمات نشر المشروع في Claude Code

## الخطوة 1: فتح Claude Code

افتح Terminal على جهازك واذهب إلى مجلد المشروع:

```bash
cd ~/Downloads/ED641-project
claude
```

## الخطوة 2: أرسل هذه الرسالة لـ Claude Code

انسخ والصق هذا النص كاملاً في Claude Code:

```
ارفع كل الملفات في هذا المجلد إلى المستودع التالي على GitHub:
https://github.com/mohdhadhrami/ED641

الخطوات المطلوبة:
1. تهيئة git في هذا المجلد إذا لم يكن مهيأ
2. ربط remote بـ https://github.com/mohdhadhrami/ED641.git
3. إضافة جميع الملفات (index.html, aou-logo.png, README.md, .gitignore)
4. عمل commit برسالة: "Add ED641 comprehensive statistical guide"
5. push إلى branch main
6. تفعيل GitHub Pages على branch main / root

الملفات في المجلد:
- index.html (الصفحة الرئيسية)
- aou-logo.png (شعار الجامعة)
- README.md (وصف المستودع)
- .gitignore

بعد الانتهاء، أعطني رابط الموقع المباشر.
```

## الخطوة 3: المصادقة

سيطلب منك Claude Code تسجيل الدخول إلى GitHub (إن لم تكن مسجلاً) — تابع التعليمات في Terminal.

## ✅ النتيجة المتوقعة

بعد ~2 دقيقة سيكون الموقع على:
**https://mohdhadhrami.github.io/ED641**

---

## بديل: أوامر يدوية إن أردت

```bash
cd ~/Downloads/ED641-project
git init
git remote add origin https://github.com/mohdhadhrami/ED641.git
git add .
git commit -m "Add ED641 comprehensive statistical guide"
git branch -M main
git push -u origin main --force
```
