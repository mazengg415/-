# FiveM Police Operations Portal

## التشغيل

لم يعد الموقع يحتاج إلى اسم مستخدم أو كلمة مرور. يفتح مباشرة عند تشغيله.

```bash
npm install
npm start
```

ثم افتح `http://localhost:3000`.

المميزات: SQLite، لوحة تحكم، حضور الضباط، الرتب الإنجليزية من Cadet إلى Chief of Police، تقارير، warrants، dispatch، rules، applications، وDiscord webhook.

واجهة FiveM محمية بمفتاح `x-fivem-key` عبر `GET /api/fivem/officers`. لا تشارك هذا المفتاح مع المستخدمين.
