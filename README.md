# king-chat-app
king-chat-app
# 👑 King Chat - تطبيق دردشة عشوائية

<div align="center">
  
![King Chat Logo](https://img.shields.io/badge/King%20Chat-👑-yellow)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Firebase](https://img.shields.io/badge/Built%20with-Firebase-orange)

**تطبيق دردشة عشوائية متقدم مع مطابقة ذكية للمستخدمين**

[![Deploy to GitHub Pages](https://github.com/king-chat/king-chat-app/actions/workflows/deploy.yml/badge.svg)](https://github.com/king-chat/king-chat-app/actions/workflows/deploy.yml)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fking-chat.github.io%2Fking-chat-app)](https://king-chat.github.io/king-chat-app)

</div>

## ✨ المميزات الرئيسية

### 🔥 ميزات أساسية
- ✅ دردشة عشوائية مع مستخدمين حول العالم
- ✅ نظام مطابقة ذكي بناءً على الاهتمامات
- ✅ دردشة خاصة (Private Chat)
- ✅ دردشة جماعية (Group Chat)
- ✅ مكالمات صوتية وفيديو (قيد التطوير)

### 🛡️ الأمان والخصوصية
- ✅ مصادقة آمنة (Email، Google، Facebook)
- ✅ تشفير الرسائل من طرف إلى طرف
- ✅ إخفاء الهوية (Anonymous Mode)
- ✅ إمكانية حظر المستخدمين
- ✅ إخفاء رقم الهاتف والأمور الشخصية

### 🎨 واجهة مستخدم
- ✅ تصميم متجاوب يعمل على جميع الأجهزة
- ✅ سمة فاتحة وداكنة (Light/Dark Mode)
- ✅ إشعارات فورية
- ✅ أصداء صوتية للرسائل
- ✅ إيموجي وملفات ميديا

### 📊 الإدارة والتقارير
- ✅ لوحة تحكم للمشرفين
- ✅ نظام تقارير للمستخدمين
- ✅ إحصائيات استخدام
- ✅ نسخ احتياطي للبيانات

## 🚀 البدء السريع

### المتطلبات الأساسية
- حساب [Firebase](https://firebase.google.com)
- حساب [GitHub](https://github.com)
- متصفح ويب حديث

### التثبيت
```bash
# استنسخ المشروع
git clone https://github.com/yourusername/king-chat-app.git
cd king-chat-app

# افتح المشروع في متصفحك
# أو استخدم VS Code Live Server
```

إعداد Firebase

1. أنشئ مشروع جديد في Firebase Console
2. أضف تطبيق ويب
3. انسخ معلومات التكوين
4. أنشئ ملف src/firebase/config.js وضبطه

```javascript
// في src/firebase/config.js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

🏗️ هيكل المشروع

```
king-chat-app/
├── public/              # ملفات الاستضافة
├── src/                # الكود المصدري
├── docs/               # التوثيق
├── config/             # الإعدادات
└── .github/           # إعدادات GitHub
```

📱 المميزات الفنية

التقنيات المستخدمة

· Frontend: HTML5, CSS3, JavaScript (ES6+)
· Backend: Firebase (Auth, Firestore, Storage, Functions)
· UI Framework: Tailwind CSS / Bootstrap
· Icons: Font Awesome 6
· Deployment: GitHub Pages

قواعد البيانات

· Users Collection: بيانات المستخدمين
· Chats Collection: غرف الدردشة
· Messages Collection: الرسائل
· Reports Collection: التقارير
· Analytics Collection: الإحصائيات

🔧 التطوير

إعداد بيئة التطوير

1. استنسخ المشروع
2. افتحه في محرر نصوص (VS Code)
3. استخدم Live Server للتجربة
4. استخدم GitHub Desktop للتحكم بالإصدارات

السكريبتات المتاحة

```bash
# فتح المشروع محلياً
open index.html

# أو استخدام VS Code Live Server
# اضغط Go Live في الزاوية السفلية
```

🌐 النشر

النشر على GitHub Pages

1. اذهب إلى إعدادات المستودع
2. اختر Pages من القائمة الجانبية
3. اختر الفرع الرئيسي (main)
4. اختر المجلد /root
5. احفظ التغييرات

النطاق المخصص

· الافتراضي: https://yourusername.github.io/king-chat-app
· يمكن إضافة نطاق مخصص من إعدادات GitHub Pages

📄 الرخصة

هذا المشروع مرخص تحت رخصة MIT. انظر ملف LICENSE للتفاصيل.

👨‍💻 مطور المشروع

معلومات المطور

· الاسم: علي قتيبة
· البريد الإلكتروني: aliqateebah@gmail.com
· الهاتف: +967781208883
· واتساب: +967783265552
· البلد: اليمن

وسائل التواصل

· 📧 البريد الإلكتروني: aliqateebah@gmail.com
· 📱 واتساب: +967783265552
· 💬 تلجرام: @yourtelegram

🤝 المساهمة

نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:

1. Fork المشروع
2. أنشئ فرعاً للميزة الجديدة (git checkout -b feature/AmazingFeature)
3. احفظ التغييرات (git commit -m 'Add some AmazingFeature')
4. ادفع إلى الفرع (git push origin feature/AmazingFeature)
5. افتح Pull Request

إرشادات المساهمة

· اكتب تعليقات واضحة في الكود
· اختبر التغييرات قبل الرفع
· اتبع أسلوب الترميز الحالي
· تحديث التوثيق عند التغيير

🐛 الإبلاغ عن الأخطاء

لإبلاغ عن أخطاء أو مشاكل:

1. اذهب إلى Issues
2. اضغط على "New Issue"
3. اختر قالب "Bug Report"
4. املأ المعلومات المطلوبة

💡 أفكار لتطوير المشروع

· إضافة مكالمات فيديو
· ترجمة لواجهة متعددة اللغات
· تطبيق هاتف (React Native)
· نظام تبرعات داخل التطبيق
· ألعاب داخل الدردشة

⭐ الدعم

إذا أعجبك المشروع، لا تنسى:

· ⭐ Star المشروع على GitHub
· 🍴 Fork المشروع
· 🔔 Watch للمتابعة
· 💬 شارك التطبيق مع أصدقائك

📞 الدعم الفني

للحصول على دعم فني:

1. تواصل عبر البريد الإلكتروني
2. أو عبر واتساب
3. أو افتح Issue على GitHub

📊 إحصائيات المشروع

https://img.shields.io/github/stars/yourusername/king-chat-app?style=social
https://img.shields.io/github/forks/yourusername/king-chat-app?style=social
https://img.shields.io/github/issues/yourusername/king-chat-app
https://img.shields.io/github/issues-pr/yourusername/king-chat-app

---

<div align="center">

مصنوع بـ ❤️ في اليمن

https://img.shields.io/badge/🇾🇪-Yemen-red

</div>
```
