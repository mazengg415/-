# FiveM Police Operations Portal

## تشغيل

```bash
npm install
cp .env.example .env
# غيّر ADMIN_PASSWORD
npm start
```

افتح `http://localhost:3000`.

المميزات: SQLite، لوحة تحكم، حضور الضباط، الرتب الإنجليزية من Cadet إلى Chief of Police، تقارير، warrants، dispatch، rules، applications، Discord webhook، وواجهة FiveM محمية بمفتاح `x-fivem-key` عبر `GET /api/fivem/officers`.

لإضافة بوت Discord حقيقي، أضف Discord.js إلى المشروع واربط أوامر slash بنفس API؛ حالياً يتم إرسال إشعارات الأحداث عبر `DISCORD_WEBHOOK_URL`.
