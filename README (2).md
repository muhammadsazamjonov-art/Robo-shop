# RoboShop (Node.js + Express)

Fayllar: server.js, index.html, package.json, render.yaml

## Render (Web Service)
- Runtime: Node
- Root Directory: bo'sh
- Build Command: npm install
- Start Command: npm start
- Environment: ADMIN_USER=ibrohim, ADMIN_PASS=2013 (ixtiyoriy, parolni o'zgartirish uchun)

Admin: saytingiz/#admin  (login: ibrohim, parol: 2013)

## Ma'lumotlar
Hamma narsa data/db.json faylida saqlanadi. Render bepul rejasida disk doimiy emas:
qayta ishga tushganda ma'lumotlar o'chadi. Doimiy saqlash uchun pullik Disk ulang
(Mount Path: /var/data) va Environment'ga DATA_DIR=/var/data qo'shing.

ADMIN_USER/ADMIN_PASS faqat birinchi marta (admin yo'q bo'lganda) ishlaydi.
