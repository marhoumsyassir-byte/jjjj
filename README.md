# AutoFlow v2.0 — WhatsApp AI Platform

## تشغيل المشروع

### 1. تثبيت المكتبات
```bash
npm install
npx puppeteer browsers install chrome
```

### 2. (اختياري) إعداد المتغيرات
```bash
# أنشئ ملف .env
GEMINI_API_KEY=AIza...
PORT=3000
```

### 3. تشغيل السيرفر
```bash
node server.js
```

افتح: **http://localhost:3000**

---

## المزايا
- ✅ **بدون تسجيل دخول** — وصول مباشر للداشبورد
- 📱 ربط واتساب بـ QR مباشرة
- 🤖 Gemini 1.5 Flash + GPT-4o Mini
- 🔢 إدارة عدة حسابات في نفس الوقت
- 📚 قاعدة معرفة لكل حساب
- 💬 محادثات مع Labels (Hot/Warm/Cold)
- 📊 إحصائيات مع رسوم بيانية
- 🏠 صفحة ويب مع الداشبورد

## على VPS (Hostinger/DigitalOcean)
```bash
npm install -g pm2
pm2 start server.js --name autoflow
pm2 save && pm2 startup
```
